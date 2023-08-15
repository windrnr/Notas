# Arrays

![[Arrays]]

```typescript
const a = new ArrayBuffer(6);
console.log(a);
// ArrayBuffer { [Uint8Contents] : <00 00 00 00 00 00>, byteLength: 6 }
cont a8 = new Uint8Array(a);
a8[0] = 45;
a8[2] = 45;
console.log(a8);
//Uint8Array(6) [ 45, 0, 45, 0, 0, 0]
const a16 = new Uint16Array(a);
a16[2] = 0x4545;
console.log(a16);
//Uint16Array(3) [ 45, 45, 17733 ]
console.log(a8);
//Uint8Array(6) [ 45, 0, 45, 0, 69, 69]
```

# Linear Search

![[Linear Search]]

```typescript
function linear_search(haystack: number[], needle:number): boolean {
	for (let i = 0; i < haystack.length; i++) {
		if (haystack[i] === needle){
		return true;
		}
	}
	return false;
}
```
# Binary Search
![[Binary Search]]

```Pseudocode
Search(hi, lo, n, arr)
m = lo + (hi - lo) / 2
v = arr[m]
do {
	if v = n
		return true;
	else if v < n
		lo = m + 1
	else
		hi = m
} while(lo < hi)
return false;
```

```typescript
function binary_fn(haystack: number[], needle: number): boolean {
	let lo = 0;
	let hi = haystack.length;
	do {
		const m = Math.floor(lo + (hi - lo) / 2)
		const v = haystack[m];

		if (v === needle) {
			return true;
		} else if (v < needle){
			lo = m + 1;
		} else 
			hi = m;
		}
	} while (lo < hi);
	return false;
}
```
## Crystal Ball Problem
Given two crystal balls that will break if dropped from a high enough distance, determine the exact spot in which it will break in the most optimized way.
![[Crystal Ball problem]]
``` TypeScript
function two_crystal_balls(breaks: boolean[]): number {
    const jmpAmount = Math.floor(Math.sqrt(breaks.length));
    
    let i = jmpAmount;
    for (; i < breaks.length; i += jmpAmount) {
        if (breaks[i]) {
            break;
        }
    }
    
    i -= jmpAmount;

    for(let j = 0; j < jmpAmount && i < breaks.length; ++j, i++){
        if (breaks[i]){
            return i;
        }
    }
    return -1
}
```

# Bubble Sort
![[Bubble Sort]]
```TypeScript
function bubble_sort(arr: number[]): void {
	for(let i = 0; i < arr.length; ++i){
		for(let j = 0 ;j < arr.length-1-i; ++j){
			if(arr[j] > arr[j + 1]) {
				const temp = arr[j];
				arr[j] = arr[j + 1];
				arr[j + 1] = temp;
			}
		}
	}
}
```
# Linked-List
![[Linked List]]

```TypeScript
//General API for LinkedList in the course
interface LinkedList<T>{
	get length(): number;
	insertAt(item: T, index: number): void;
	remove(item: T): T | undefined;
	removeAt(index:number): T | undefined;
	append(item: T): void;
	prepend(item: T): void;
	get(index: number): T | undefined;
}
```
## Queue / Fila (FIFO)
![[Queue]]
```typescript
type QNode<T> = {
    value: T,
    next?: QNode<T>,
}

class Queue<T> {
    public length: number;
    private head?: QNode<T>; // same as head: Node <T> | undefined
    private tail?: QNode<T>;

    constructor(){
        this.head = this.tail = undefined;
        this.length = 0;
    }

    enqueue(item:T):void {
        const node = {value: item} as QNode<T>;
        this.length++;
        if (!this.tail){
            this.tail = this.head = node;
        }

        this.tail.next = node;
        this.tail =  node;
    }

    deque(): T | undefined {
        if (!this.head) {
            return undefined;
        }

        this.length--;
        const head = this.head;
        this.head = this.head.next;
        
        //free if we would not have a garbage collector and this next step is not necessary
        head.next = undefined;
        
    if(this.lenght === 0){
	    this.tail = undefined;
	}

        return head.value;
    }

    peek(): T | undefined {
        return this.head?.value;
    }
}
```
## Stack/Cola (FILO)
![[Stack]]

```typescript
type QNode<T> = {
    value: T,
    prev?: QNode<T>,
}

export class Stack<T> {
    public length: number;
    private head?: QNode<T>; // same as head: Node <T> | undefined

    constructor(){
        this.head = undefined;
        this.length = 0;
    }

    push(item:T):void {
        const node = {value: item} as QNode<T>;
        this.length++;
        if (!this.head){
            this.head = node;
            return;
        }

        node.prev = this.head;
        this.head = node;
    }

    pop(): T | undefined {
        this.length = Math.max(0, this.length - 1);

        if (this.length === 0){
            const head = this.head; 
            this.head = undefined;
            return head?.value;
        }

        const head = this.head as QNode<T>;
        this.head = head.prev;
        
        // free
        head.prev = undefined;

        return head.value;
    }

    peek(): T | undefined {
        return this.head?.value;
    }
}
```
# Array vs LinkedList
## Usability
- **Arrays**: In an array one can use a index access, and the mechanics behind are simple. Problems arise because we dont have a literal Insert, we can only Write. We can't really insert a value inside an array without using a for loop to shift every element and putting the value or having to unshift everything to "delete" writing over the value. We have to always alocate all the memory we are going to use upfront, it doesn't matter if we dont use it all.
- **Linked-Lists**: The memory usage is optimized because its allocated only when creating a new node. The difference lies in runtime costs, because an array will already have retrieved the memory it will use, therefore making it faster, where like we said in a list you are creating a containing node each time you want to insert something.
   Because there's no other way than traversing each element in the list in order to get a specific node (it's always a Linear Search), it can't take advantage of better searching algorithms.
      
   Arrays and Linked-Lists present a series or trade-offs when using each of them, the answer always lies in the case and what purpose we are using them for.
   For example: In terms of needing to scan a list or do a random access we would need something like an Array, but if we need to push or pop elements we would prefer a Linked-List.
## Time
- **Arrays**: They are very efficient since every action is O(1).
- **Linked-Lists**: They are fast when pushing/queueing (O(1)), but when having to get a certain node or random access to one of them, the operation will always be O(N), therefore becoming extremely slow in large lists.
# ArrayLists
![[ArrayLists]]
Array Lists operate best when treated like a Stack. But a Queue can greatly benefit of index access although losing remove from the front.
A demostration of this can be seen if we run the following code:
```typescript
const a: number[] = [];

function time(fn: () => void): number {
    const now = Date.now();
    fn();
    return Date.now() - now;
}

function unshift(number: number){
    for (let i = 0; i < number; ++i){
        a.unshift(Math.random());
    }
}

function shift(number: number){
    for (let i = 0; i < number; ++i) {
        a.shift();
    }
}

function push(number: number){
    for (let i = 0; i < number; ++i){
        a.push(Math.random());
    }
}

function pop(number: number){
    for (let i = 0; i < number; ++i){
        a.pop();
    }
}

function get(idx: number){
    return function(){
        return a[idx];
    };
}

function push_arr(count: number){
    return function(){
        push(count);
    }
}

function pop_arr(count: number){
    return function(){
        pop(count);
    }
}

function unshift_arr(count: number){
    return function(){
        unshift(count);
    }
}

function shift_arr(count: number){
    return function(){
        shift(count);
    }
}

const tests= [10, 100, 1000, 10000, 100000, 1_000_000, 10_000_000];
console.log("Testing get");
tests.forEach(t => {
    a.length = 0;
    push(t);
    console.log(t, time(get(t - 1)));
});

console.log("push");
tests.forEach(t => {
    a.length = 0;
    push(t);

    console.log(t, time(push_arr(1000)));
});

console.log("pop");
tests.forEach(t => {
    a.length = 0;
    push(t);

    console.log(t, time(pop_arr(1000)));
});

console.log("unshift");
tests.forEach(t => {
    a.length = 0;
    push(t);

    console.log(t, time(unshift_arr(1000)));
});

console.log("shift");
tests.forEach(t => {
    a.length = 0;
    push(t);

    console.log(t, time(shift_arr(1000)));
});
```

# ArrayBuffer
![[ArrayBuffer]]

# Recursion
![[Recursion]]
```TypeScript
function foo(n:number) number {
	if (n === 1){
		return 1;
	}
	const out = n + foo(n - 1);
	console.log(n);
	return out;
}
console.log(foo(5))
```
![[Maze Solver]]
```typescript
const dir = [
    [-1, 0],
    [1, 0],
    [0, -1],
    [0, 1],
];

export type Point = {
    x: number,
    y: number,
}

export function walk(maze: string[], wall: string, curr: Point, end: Point, seen: boolean[][], path: Point[]): boolean{
 
    //off the map
    if (curr.x < 0 || curr.x >= maze[0].length || curr.y < 0 || curr.y >= maze.length){
        return false;
    }

    //on a wall
    if (maze[curr.y][curr.x] === wall){
        return false;
    }

    //the end
    if (curr.x === end.x && curr.y === end.y){
        path.push(end);
        return true;
    }
    
    if (seen[curr.y][curr.x]){
        return false;
    }

    //3 Recurse steps
    //pre
    seen[curr.y][curr.x] = true;
    path.push(curr);
    //recurse
    for (let i = 0; i < dir.length; ++i){
        const [x, y] = dir[i];
        if (walk(maze, wall, {
            x: curr.x + x,
            y: curr.y + y,
        }, end, seen, path)) {
            return true;
        }
    }
    //post
    path.pop();

    return false;
}

export function maze_solver(maze: string[], wall: string, start: Point, end: Point): Point[]{
    const seen: boolean[][] = [];
    const path: Point[] = [];

    for (let i = 0; i < maze.length; ++i){
        seen.push(new Array(maze[0].length).fill(false));
    }

    walk(maze, wall, start, end, seen, path);
    return path;
}

```
# QuickSort
![[Quick Sort]]
![[QuickSort graphic]]

```TypeScript
function qs (arr: number[], lo: number, hi: number): void {
    if (lo >= hi) {
        return;
    }

    const pivotIdx = partition(arr, lo, hi);

    // we always ignore the pivot each time we divide the array
    qs(arr, lo, pivotIdx - 1);
    qs(arr, pivotIdx + 1, hi);
}

function partition(arr: number[], lo: number, hi: number): number {
    //This could cause a reverse sorting issue where we hit the worst case scenario for Big O.
    const pivot = arr[hi];

    let idx = lo - 1;

    for (let i = lo; i < hi; ++i){
        if (arr[i] <= pivot) {
            //We compare each element to the pivot and swap if necessary
            idx++;
            const tmp =  arr[i];
            arr[i] = arr[idx];
            arr[idx] = tmp;
        }
    }
    // With nothing else to do we move the pivot to the pivot index
    idx++;
    arr[hi] = arr[idx];
    arr[idx] = pivot;

    return idx;
}

export function quick_sort(arr: number[]): void{
    qs(arr, 0, arr.length - 1);
}
```
# Doubly Linked List
```TypeScript
export class LinkedList<T> {
    public length: number;
    private head?: QNode<T>;
    private tail?: QNode<T>;

    constructor (){
        this.length = 0;
        this.head = undefined;
        this.tail = undefined;
    }

    prepend(item: T): void {
        const node = {value: item} as QNode<T>;
        this.length++;
        if (!this.head) {
            this.head = this.tail = node;
            return;
        }        

        node.next = this.head;
        this.head.prev = node;
        this.head = node;
    }

    insertAt(item: T, idx:number): void {
        if (idx > this.length) {
            throw new Error("Index greater than Length");
        }

        if (idx === this.length) {
            this.append(item);
            return;
        } else if (idx === 0) {
            this.prepend(item);
            return;
        }

        this.length++;
        const curr = this.getAt(idx) as QNode<T>;
        const node = {value: item} as QNode<T>;

        node.next = curr;
        node.prev = curr.prev;
        curr.prev = node;

        if(node.prev) {
            node.prev.next = node;
        }
    }

    append(item: T): void {
        this.length++;
        const node = {value:item} as QNode<T>;
        if (!this.tail){
            this.head = this.tail = node;
            this.debug();
            return;
        }
        node.prev = this.tail;
        this.tail.next = node;
        this.tail  = node;
        this.debug();
    }

    remove(item: T): T | undefined {
        let curr = this.head;
        for (let i = 0; i < this.length && curr; ++i){
            if (curr.value === item) {
                break;
            }
            curr = curr.next;
        }
        if (!curr) {
            return undefined;
        }    
        return this.removeNode(curr);
    }

    get(idx: number): T | undefined {
        return this.getAt(idx)?.value;
    }

    removeAt(idx: number): T | undefined{
        const node = this.getAt(idx);
        if(!node) {
            return undefined;
        }
        return this.removeNode(node);
    }

    private removeNode(node: QNode<T>): T | undefined{

        this.length--;
        if (this.length === 0) {
            const out = this.head?.value;
            this.head = this.tail = undefined;
            return out;
        }
        
        if(node.prev){
            node.prev.next = node.next;
        }

        if(node.next) {
            node.next.prev = node.prev;
        }

        if (node === this.head) {
            this.head = node.next;
        }

        if (node === this.tail) {
            this.tail = node.prev;
        }

        node.prev = node.next = undefined;

        return node.value;
    }

    private debug() {
        let curr = this.head;
        let out = "";
        for (let i = 0; curr && i < this.length; ++i){
            out += `${i} => ${curr.value} `;
            curr = curr.next;
        }
        console.log(out);
    }

    private getAt(idx:number): QNode<T> | undefined {
        let curr = this.head;
        for (let i = 0; curr && i < idx; ++i){
            curr = curr.next;
        }
        return curr;
    }
}
```
# Trees
- Terminology
	- Root - the most parent node.
	- Height - The longest path from the root to the most    child node.
	- Binary Tree - A tree in which has at mot 2 children, at  least 0 children.
	- General Tree - A tree with 0 or more children.
	- Binaryt Search Tree - A tree which has a specific  ordering to the nodes and at most 2 children-
	- Leaves - a node without children.
	- Balanced - A tree is perfectly balanced when any node's  left and right children have the same height.
	- Branching Factor - The amount of children a tree has.
	![[Binary Tree]]
## Traversals:
### Depth-first Traversal
![[Depth-First Traversal]]
- PreOrder:   0 1 9 3 5 2 8 6 7
- InOrder:      3 9 5 1 2 0 6 8 7
- PostOrder: 3 5 9 2 1 6 7 8 0
We use an implicit Data-Structure (a Stack) because the way the recursion is called.
When doing a comparison between different trees structures and values, Depth-First is useful because it preserves the shape of the tree.

### Breadth-first Traversal
We use an implicit Data-Structure (a Queue).
![[Breadth-First Traversal]]
We should use a Queue to implement this algorithm, else we wil have poor perfomance.
In the code example we are using javascript ArrayLists, so the Big O notation turns to O(n^2), because the shift and unshift (deque and enqueue) are O(N) on ArrayLists.
![[BFT pseudocode]]
```TypeScript
export function bfs(head: BinaryNode<number>, needle: number): boolean {
    const q: (BinaryNode<number> | null)[] = [head];

    while(q.length){
        const next = q.shift() as BinaryNode<number> | undefined | null ;
        if(!next){
            continue;
        }

        if(next.value === needle) {
            return true;
        }
        
        q.push(next.left);
        q.push(next.right);
    }

    return false;
}
```

When doing a comparison between different trees structures and values, Breadth-First does not preserve the shape of the tree.
## Compare two Trees
```typescript
export function compare(a: BinaryNode<number> | null, b: BinaryNode<number> | null): boolean {
    if (a === null && b === null) {
        return true;
    }

    if (a === null || b === null) {
        return false;
    }

    if (a.value !== b.value){
        return false;
    }
    return compare(a.left, b.left) && compare(a.right, b.right);
}
```
## Binary Search Tree (BST)
![[Binary Search Tree]]
# Heap  
## Priority Queue
![[Priority Queue]]
It is a binary tree where every child and grand child is smaller (MaxHeap), or larger (MinHeap) than the current node.
![[Heap condition]]
- Whenever a node is added, we must adjust the tree.
- Whenever a node is deleted, we must adjust the tree.
- There is no traversing the tree.
- It's self balancing.
- It can be used for priority.
## Trie
Generally called, Trie Trees, Try Trees, Prefix Tree or Digital tree.
It can do it in O(1) given that the keys need a certain length given that the keys need a certain length. 
![[Trie]]
For example. if someone typed a "c" and we wanted to show them a list of the possible words we would ahve to do a Depth-First search or do a Breadth-First search depending on the order we want to display the options. If we want to show them by alphabetical order a Depth-First search will always display them in that order, using a PreOrder traversal.
Also, to know the right words to show, we could include a score or frecuency trait.
![[Trie functions]]

# Graphs
![[Graphs]] 
## Graph Terms:
- cycle: When you start at Node(x), follow the links, and end back at Node(x).
- acyclic: A graph that contains no cycles.
- connected: When every node has a path to another node.
- directed: When there is a direction to the connections. Think Twitter.
- undirected: !directed.
- weighted: The edges have a weight associated with them. Think Maps.
- dag: Directed, acyclic graph.
## Implementation terms:
- node: a point or vertex on the graph = Vertex.
- edge: the connect betxit two nodes.
## Big O
Big O is commonly stated in terms of V and E where V stands for vertices and E stands for edges. So O(V * E) means that we well check every vertex, and on every vertex we check every edge.
## How are graphs represented:
The list is ordered by use (the most used first).
- **Adj list** 
- Adj Matrix O(V^2).
- A graph node.

An Adjancency List is basically a list of edges, where the index of the list match the node in question.
![[Adjacency List and Matrix]]
Just for fun, we are going to implement a BFS on an Adj. Matrix and a DFS on an Adj. List. (note that the algorithms doesn't change because trees are essentially graphs)
