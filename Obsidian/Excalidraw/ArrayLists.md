---

excalidraw-plugin: parsed
tags: [excalidraw]

---
==⚠  Switch to EXCALIDRAW VIEW in the MORE OPTIONS menu of this document. ⚠==


# Text Elements
Length: 1
Capacity: 3 ^mTFlRRHF

3 ^gDrcEj69

0 ^h3MLbhph

[2,    ] ^31GFOQez

push(val:T) ^VE7kH1Xu

pop(): T | undefined ^EDh1cEtL

ArrayList ^N2pLP2Ey

If we push and our length goes outside the boundaries
 of the array capacity, we can create a new array with
 more capacity and do a memcopy of every element
 of the old array to the new. ^zf0Ug3ip

[2, x, y,     ] ^aWy8CBQZ

6 ^XaKxb2Ga

0 ^9asHV7XH

[2, 3, 5] ^QmMciZnK

Length: 3
Capacity: 3 ^pF34Caxw

If we want to enqueue in this array, we would have to create a
new array with more capacity (like with push) but we face the
problem that we have to insert it on the "head" (in this case the
first element of the old array), but in arrays one can only write,
so we would be overwriting the value stored there. To solve this
we shift the entire array one element to the right so we free the spot. ^2DpMUSoX

[2, 3, 5      ] ^OrHUJDut

0 ^D8q0QDCW

0 ^bdPmeIdL

3 ^l4rnFab5

6 ^irOkPnV3

Length: 3
Capacity: 6 ^7CMltjGL

The same will be done when wanting to deque, we will have to shift
 all the elements to the left and overwrite the first element. ^So33P6f9

1) ^d9lIvNYM

2) ^RhtZxOA0

enqueue(val:t) ^xxSXOi09

deque(): T | undefined ^1EUW6HuR

O(1) ^OjLfjhML

O(N) ^LGA2Ypkw

%%
# Drawing
```json
{
	"type": "excalidraw",
	"version": 2,
	"source": "https://github.com/zsviczian/obsidian-excalidraw-plugin/releases/tag/1.8.20",
	"elements": [
		{
			"type": "text",
			"version": 244,
			"versionNonce": 701984776,
			"isDeleted": false,
			"id": "mTFlRRHF",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -97,
			"y": -182.2142857142857,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 112.9798583984375,
			"height": 48,
			"seed": 1964099192,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679752210563,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Length: 1\nCapacity: 3",
			"rawText": "Length: 1\nCapacity: 3",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Length: 1\nCapacity: 3"
		},
		{
			"type": "text",
			"version": 221,
			"versionNonce": 362640504,
			"isDeleted": false,
			"id": "gDrcEj69",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -141,
			"y": -151.5,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 23.207199096679688,
			"height": 40.8,
			"seed": 1730032904,
			"groupIds": [],
			"roundness": null,
			"boundElements": [
				{
					"id": "6a0XS65cNZ-a7MqBmjauE",
					"type": "arrow"
				}
			],
			"updated": 1679752210563,
			"link": null,
			"locked": false,
			"fontSize": 34.095607235142126,
			"fontFamily": 1,
			"text": "3",
			"rawText": "3",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "3"
		},
		{
			"type": "text",
			"version": 209,
			"versionNonce": 880553736,
			"isDeleted": false,
			"id": "h3MLbhph",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -320,
			"y": -147.5,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 24.74652099609375,
			"height": 42,
			"seed": 1971933448,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679752210563,
			"link": null,
			"locked": false,
			"fontSize": 35.98837847578387,
			"fontFamily": 1,
			"text": "0",
			"rawText": "0",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "0"
		},
		{
			"type": "text",
			"version": 414,
			"versionNonce": 65545592,
			"isDeleted": false,
			"id": "31GFOQez",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -319,
			"y": -194.5,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 203.50698852539062,
			"height": 61.199999999999996,
			"seed": 493549176,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679752210563,
			"link": null,
			"locked": false,
			"fontSize": 51.404039019083434,
			"fontFamily": 1,
			"text": "[2,    ]",
			"rawText": "[2,    ]",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "[2,    ]"
		},
		{
			"type": "text",
			"version": 246,
			"versionNonce": 707857928,
			"isDeleted": false,
			"id": "VE7kH1Xu",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 54.14285714285714,
			"y": -187.35714285714283,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 106.9998779296875,
			"height": 24,
			"seed": 1334562424,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679752210563,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "push(val:T)",
			"rawText": "push(val:T)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "push(val:T)"
		},
		{
			"type": "text",
			"version": 267,
			"versionNonce": 397719160,
			"isDeleted": false,
			"id": "EDh1cEtL",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 53.428571428571416,
			"y": -153.78571428571428,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 188.91978454589844,
			"height": 24,
			"seed": 2145556600,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679752210563,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "pop(): T | undefined",
			"rawText": "pop(): T | undefined",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "pop(): T | undefined"
		},
		{
			"type": "rectangle",
			"version": 285,
			"versionNonce": 1945242888,
			"isDeleted": false,
			"id": "uzMpIVj5ipCV95UGEKlwj",
			"fillStyle": "hachure",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 32.85714285714289,
			"y": -222.9285714285714,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 230,
			"height": 241,
			"seed": 155500040,
			"groupIds": [],
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1679752210563,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 113,
			"versionNonce": 96937848,
			"isDeleted": false,
			"id": "N2pLP2Ey",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -323,
			"y": -312.5,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 164.80807495117188,
			"height": 43.199999999999996,
			"seed": 709687160,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679752210563,
			"link": null,
			"locked": false,
			"fontSize": 36,
			"fontFamily": 1,
			"text": "ArrayList",
			"rawText": "ArrayList",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "ArrayList"
		},
		{
			"type": "text",
			"version": 384,
			"versionNonce": 2067475464,
			"isDeleted": false,
			"id": "zf0Ug3ip",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -334,
			"y": 45.5,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 448.6409912109375,
			"height": 76.8,
			"seed": 810682744,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679752210563,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "If we push and our length goes outside the boundaries\n of the array capacity, we can create a new array with\n more capacity and do a memcopy of every element\n of the old array to the new.",
			"rawText": "If we push and our length goes outside the boundaries\n of the array capacity, we can create a new array with\n more capacity and do a memcopy of every element\n of the old array to the new.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "If we push and our length goes outside the boundaries\n of the array capacity, we can create a new array with\n more capacity and do a memcopy of every element\n of the old array to the new."
		},
		{
			"type": "text",
			"version": 147,
			"versionNonce": 1248032888,
			"isDeleted": false,
			"id": "aWy8CBQZ",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -317,
			"y": -46.5,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 300.01080322265625,
			"height": 50.4,
			"seed": 1950177656,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679752210563,
			"link": null,
			"locked": false,
			"fontSize": 42.837913977812455,
			"fontFamily": 1,
			"text": "[2, x, y,     ]",
			"rawText": "[2, x, y,     ]",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "[2, x, y,     ]"
		},
		{
			"type": "text",
			"version": 82,
			"versionNonce": 436759304,
			"isDeleted": false,
			"id": "XaKxb2Ga",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -42,
			"y": -5.5,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 23.22998046875,
			"height": 43.199999999999996,
			"seed": 1370781048,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679752210563,
			"link": null,
			"locked": false,
			"fontSize": 36.31245883562563,
			"fontFamily": 1,
			"text": "6",
			"rawText": "6",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "6"
		},
		{
			"type": "text",
			"version": 107,
			"versionNonce": 961390968,
			"isDeleted": false,
			"id": "9asHV7XH",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -320,
			"y": -4.5,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 21.994552612304688,
			"height": 37.199999999999996,
			"seed": 339524872,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679752210563,
			"link": null,
			"locked": false,
			"fontSize": 31.988334151162576,
			"fontFamily": 1,
			"text": "0",
			"rawText": "0",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "0"
		},
		{
			"type": "arrow",
			"version": 240,
			"versionNonce": 181783048,
			"isDeleted": false,
			"id": "6a0XS65cNZ-a7MqBmjauE",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "dotted",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -130,
			"y": -19.5,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 1,
			"height": 87,
			"seed": 1702048520,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1679752210563,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": {
				"elementId": "gDrcEj69",
				"focus": 0.15978114617969397,
				"gap": 4.3999999999999915
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-1,
					-87
				]
			]
		},
		{
			"type": "line",
			"version": 77,
			"versionNonce": 231324280,
			"isDeleted": false,
			"id": "ePpk_eXchMbWhX98QuggF",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "dotted",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -310,
			"y": -105.5,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 1,
			"height": 56,
			"seed": 1945125240,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1679752210564,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-1,
					56
				]
			]
		},
		{
			"type": "line",
			"version": 68,
			"versionNonce": 1486833928,
			"isDeleted": false,
			"id": "xU5HNpTRvm1QxMzNEmlSK",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "dotted",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -276,
			"y": -129.5,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 3,
			"height": 77,
			"seed": 1914033672,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1679752210564,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-3,
					77
				]
			]
		},
		{
			"type": "line",
			"version": 72,
			"versionNonce": 2057022328,
			"isDeleted": false,
			"id": "H5pwVbEsfsuwqv2n8-3kH",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "dotted",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -226,
			"y": -126.5,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 79,
			"seed": 645414408,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1679752210564,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					79
				]
			]
		},
		{
			"type": "line",
			"version": 78,
			"versionNonce": 1323362312,
			"isDeleted": false,
			"id": "TlzqKpcXUi_ektJlWJkH4",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "dotted",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -167,
			"y": -124.5,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 1,
			"height": 87,
			"seed": 1464376952,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1679752210564,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-1,
					87
				]
			]
		},
		{
			"type": "rectangle",
			"version": 48,
			"versionNonce": 973569144,
			"isDeleted": false,
			"id": "WWIxBcBWoym8-HKb9f-JF",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "dotted",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -242,
			"y": -186.5,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 32,
			"height": 44,
			"seed": 778271864,
			"groupIds": [],
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1679752210564,
			"link": null,
			"locked": false
		},
		{
			"type": "freedraw",
			"version": 31,
			"versionNonce": 1771480840,
			"isDeleted": false,
			"id": "sdtGX9zD0wb10DsIla5fH",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "dotted",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -189,
			"y": -153.5,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 2,
			"height": 16,
			"seed": 1910553096,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679752210564,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1
				],
				[
					-1,
					-1
				],
				[
					-2,
					4
				],
				[
					-2,
					10
				],
				[
					-2,
					14
				],
				[
					-2,
					15
				],
				[
					-2,
					15
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "line",
			"version": 102,
			"versionNonce": 500247928,
			"isDeleted": false,
			"id": "yDYhEoAw9NuCgOAYGP1bp",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -125,
			"y": -320.5,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 215,
			"height": 72,
			"seed": 2138113400,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1679752210564,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-1,
					65
				],
				[
					-215,
					72
				]
			]
		},
		{
			"type": "text",
			"version": 216,
			"versionNonce": 1161594376,
			"isDeleted": false,
			"id": "QmMciZnK",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 325.2857142857142,
			"y": -257.5,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 162.57601928710938,
			"height": 42,
			"seed": 620966008,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679752210564,
			"link": null,
			"locked": false,
			"fontSize": 35.99999999999997,
			"fontFamily": 1,
			"text": "[2, 3, 5]",
			"rawText": "[2, 3, 5]",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "[2, 3, 5]"
		},
		{
			"type": "text",
			"version": 184,
			"versionNonce": 524074616,
			"isDeleted": false,
			"id": "pF34Caxw",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 532.2857142857142,
			"y": -250.5,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 153.93553161621094,
			"height": 64.8,
			"seed": 1033639288,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679752210564,
			"link": null,
			"locked": false,
			"fontSize": 27.25,
			"fontFamily": 1,
			"text": "Length: 3\nCapacity: 3",
			"rawText": "Length: 3\nCapacity: 3",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Length: 3\nCapacity: 3"
		},
		{
			"type": "text",
			"version": 870,
			"versionNonce": 248415496,
			"isDeleted": false,
			"id": "2DpMUSoX",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 316.14285714285705,
			"y": -59.928571428571445,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 574.0171508789062,
			"height": 115.19999999999999,
			"seed": 1829949048,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679752210564,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "If we want to enqueue in this array, we would have to create a\nnew array with more capacity (like with push) but we face the\nproblem that we have to insert it on the \"head\" (in this case the\nfirst element of the old array), but in arrays one can only write,\nso we would be overwriting the value stored there. To solve this\nwe shift the entire array one element to the right so we free the spot.",
			"rawText": "If we want to enqueue in this array, we would have to create a\nnew array with more capacity (like with push) but we face the\nproblem that we have to insert it on the \"head\" (in this case the\nfirst element of the old array), but in arrays one can only write,\nso we would be overwriting the value stored there. To solve this\nwe shift the entire array one element to the right so we free the spot.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "If we want to enqueue in this array, we would have to create a\nnew array with more capacity (like with push) but we face the\nproblem that we have to insert it on the \"head\" (in this case the\nfirst element of the old array), but in arrays one can only write,\nso we would be overwriting the value stored there. To solve this\nwe shift the entire array one element to the right so we free the spot."
		},
		{
			"type": "text",
			"version": 245,
			"versionNonce": 1863200632,
			"isDeleted": false,
			"id": "OrHUJDut",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 323.2857142857142,
			"y": -164.5,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 270.5760192871094,
			"height": 42,
			"seed": 183910664,
			"groupIds": [],
			"roundness": null,
			"boundElements": [
				{
					"id": "3EuguRfWsioz_b8IGaY1s",
					"type": "arrow"
				},
				{
					"id": "sDZE1eMdKOuczZZ1v_7YG",
					"type": "arrow"
				},
				{
					"id": "xWcVQJBRoM87SkAAMmtFc",
					"type": "arrow"
				}
			],
			"updated": 1679752210564,
			"link": null,
			"locked": false,
			"fontSize": 35.999999999999986,
			"fontFamily": 1,
			"text": "[2, 3, 5      ]",
			"rawText": "[2, 3, 5      ]",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "[2, 3, 5      ]"
		},
		{
			"type": "text",
			"version": 160,
			"versionNonce": 1942529032,
			"isDeleted": false,
			"id": "D8q0QDCW",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 323.2857142857142,
			"y": -222.5,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 16.737823486328125,
			"height": 28.799999999999997,
			"seed": 1679793016,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679752210564,
			"link": null,
			"locked": false,
			"fontSize": 24.333333333333314,
			"fontFamily": 1,
			"text": "0",
			"rawText": "0",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "0"
		},
		{
			"type": "text",
			"version": 164,
			"versionNonce": 92897400,
			"isDeleted": false,
			"id": "bdPmeIdL",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 325.2857142857142,
			"y": -127.5,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 17.888015747070312,
			"height": 30,
			"seed": 3746824,
			"groupIds": [],
			"roundness": null,
			"boundElements": [
				{
					"id": "3EuguRfWsioz_b8IGaY1s",
					"type": "arrow"
				},
				{
					"id": "l51nIGDWt2aF99bf7TtkN",
					"type": "arrow"
				}
			],
			"updated": 1679752210564,
			"link": null,
			"locked": false,
			"fontSize": 25.999999999999996,
			"fontFamily": 1,
			"text": "0",
			"rawText": "0",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "0"
		},
		{
			"type": "text",
			"version": 172,
			"versionNonce": 304538376,
			"isDeleted": false,
			"id": "l4rnFab5",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 471.2857142857142,
			"y": -221.5,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 17.6422119140625,
			"height": 30,
			"seed": 76449544,
			"groupIds": [],
			"roundness": null,
			"boundElements": [
				{
					"id": "KH43lNqKD9u0QNj9mF6Sm",
					"type": "arrow"
				}
			],
			"updated": 1679752210564,
			"link": null,
			"locked": false,
			"fontSize": 25.922860866585822,
			"fontFamily": 1,
			"text": "3",
			"rawText": "3",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "3"
		},
		{
			"type": "text",
			"version": 168,
			"versionNonce": 846377336,
			"isDeleted": false,
			"id": "irOkPnV3",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 575.2857142857141,
			"y": -129.5,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.10003662109375,
			"height": 34.8,
			"seed": 1382808184,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679752210564,
			"link": null,
			"locked": false,
			"fontSize": 29.85413183527293,
			"fontFamily": 1,
			"text": "6",
			"rawText": "6",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "6"
		},
		{
			"type": "arrow",
			"version": 277,
			"versionNonce": 1751466504,
			"isDeleted": false,
			"id": "KH43lNqKD9u0QNj9mF6Sm",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "dotted",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 483.2857142857142,
			"y": -147.5,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 3,
			"height": 39,
			"seed": 1777668984,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1679752210564,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": {
				"elementId": "l4rnFab5",
				"focus": -0.7651364619662021,
				"gap": 3.8925669600970423
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					3,
					-39
				]
			]
		},
		{
			"type": "line",
			"version": 163,
			"versionNonce": 755876472,
			"isDeleted": false,
			"id": "9yTSNLlGqv8ApoUeS0oJn",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "dotted",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 455.2857142857142,
			"y": -165.5,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 48,
			"seed": 1076767608,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1679752210564,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-48
				]
			]
		},
		{
			"type": "line",
			"version": 158,
			"versionNonce": 1166000392,
			"isDeleted": false,
			"id": "fesyJtLZGiuOEPvkkvpOT",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "dotted",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 404.2857142857142,
			"y": -209.5,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 2,
			"height": 43,
			"seed": 992792440,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1679752210564,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					2,
					43
				]
			]
		},
		{
			"type": "line",
			"version": 156,
			"versionNonce": 605991800,
			"isDeleted": false,
			"id": "zuw8zqPh3lih-r1CVt5mi",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "dotted",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 351.2857142857142,
			"y": -214.5,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 1,
			"height": 46,
			"seed": 1651511560,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1679752210564,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-1,
					46
				]
			]
		},
		{
			"type": "arrow",
			"version": 459,
			"versionNonce": 955408392,
			"isDeleted": false,
			"id": "3EuguRfWsioz_b8IGaY1s",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 353.2857142857142,
			"y": -119.5,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 48,
			"height": 18,
			"seed": 1029823752,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1679752210564,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "bdPmeIdL",
				"focus": -1.008358308313159,
				"gap": 10.111984252929688
			},
			"endBinding": {
				"elementId": "OrHUJDut",
				"focus": 0.1366285843464126,
				"gap": 2
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					21,
					17
				],
				[
					48,
					-1
				]
			]
		},
		{
			"type": "arrow",
			"version": 393,
			"versionNonce": 1307149432,
			"isDeleted": false,
			"id": "sDZE1eMdKOuczZZ1v_7YG",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 409.6640994771949,
			"y": -120.3380462374111,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 48,
			"height": 18,
			"seed": 439697416,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1679752210564,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "OrHUJDut",
				"focus": 0.48081523920446745,
				"gap": 2.161953762588894
			},
			"endBinding": {
				"focus": 0.14562203659280412,
				"gap": 1,
				"elementId": "OrHUJDut"
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					21,
					17
				],
				[
					48,
					-1
				]
			]
		},
		{
			"type": "arrow",
			"version": 310,
			"versionNonce": 45686536,
			"isDeleted": false,
			"id": "xWcVQJBRoM87SkAAMmtFc",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 460.6640994771949,
			"y": -117.3380462374111,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 48,
			"height": 18,
			"seed": 1121985032,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1679752210564,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "OrHUJDut",
				"focus": 0.18748052241456353,
				"gap": 5.161953762588894
			},
			"endBinding": {
				"elementId": "OrHUJDut",
				"focus": -0.5266164299191487,
				"gap": 4.161953762588894
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					21,
					17
				],
				[
					48,
					-1
				]
			]
		},
		{
			"type": "text",
			"version": 223,
			"versionNonce": 2016556408,
			"isDeleted": false,
			"id": "7CMltjGL",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 624.3179484776086,
			"y": -169.89999999999998,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 152.8182830810547,
			"height": 64.8,
			"seed": 1895298680,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679752210564,
			"link": null,
			"locked": false,
			"fontSize": 27.25,
			"fontFamily": 1,
			"text": "Length: 3\nCapacity: 6",
			"rawText": "Length: 3\nCapacity: 6",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Length: 3\nCapacity: 6"
		},
		{
			"type": "text",
			"version": 328,
			"versionNonce": 55574024,
			"isDeleted": false,
			"id": "So33P6f9",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 316.7142857142856,
			"y": 71.07142857142861,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 531.4091186523438,
			"height": 38.4,
			"seed": 1970545016,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679752210564,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "The same will be done when wanting to deque, we will have to shift\n all the elements to the left and overwrite the first element.",
			"rawText": "The same will be done when wanting to deque, we will have to shift\n all the elements to the left and overwrite the first element.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "The same will be done when wanting to deque, we will have to shift\n all the elements to the left and overwrite the first element."
		},
		{
			"type": "text",
			"version": 161,
			"versionNonce": 406636152,
			"isDeleted": false,
			"id": "d9lIvNYM",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 275.42857142857133,
			"y": -58.64285714285711,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 21.733657836914062,
			"height": 42,
			"seed": 1215411320,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679752210564,
			"link": null,
			"locked": false,
			"fontSize": 35.70439597609714,
			"fontFamily": 1,
			"text": "1)",
			"rawText": "1)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1)"
		},
		{
			"type": "text",
			"version": 170,
			"versionNonce": 733150472,
			"isDeleted": false,
			"id": "RhtZxOA0",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 271.42857142857133,
			"y": 71.78571428571433,
			"strokeColor": "#e67700",
			"backgroundColor": "transparent",
			"width": 33.41957092285156,
			"height": 37.199999999999996,
			"seed": 1577281400,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679752210564,
			"link": null,
			"locked": false,
			"fontSize": 31.833333333333343,
			"fontFamily": 1,
			"text": "2)",
			"rawText": "2)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "2)"
		},
		{
			"type": "arrow",
			"version": 191,
			"versionNonce": 1523398520,
			"isDeleted": false,
			"id": "QcNcxGW7yDz3WuFCLvRuy",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 505.8571428571428,
			"y": -91.42857142857144,
			"strokeColor": "#e67700",
			"backgroundColor": "transparent",
			"width": 48.571428571428555,
			"height": 20,
			"seed": 747189000,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1679752210564,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-21.428571428571445,
					8.571428571428555
				],
				[
					-48.571428571428555,
					-11.428571428571445
				]
			]
		},
		{
			"type": "arrow",
			"version": 277,
			"versionNonce": 1834884104,
			"isDeleted": false,
			"id": "O-_pxz6tHEww_WVy46Np4",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 452.9999999999998,
			"y": -91.5596964880886,
			"strokeColor": "#e67700",
			"backgroundColor": "transparent",
			"width": 48.571428571428555,
			"height": 20,
			"seed": 1991978248,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1679752210564,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-21.428571428571445,
					8.571428571428555
				],
				[
					-48.571428571428555,
					-11.428571428571445
				]
			]
		},
		{
			"type": "arrow",
			"version": 351,
			"versionNonce": 875006072,
			"isDeleted": false,
			"id": "l51nIGDWt2aF99bf7TtkN",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 397.2857142857141,
			"y": -95.84541077380285,
			"strokeColor": "#e67700",
			"backgroundColor": "transparent",
			"width": 48.571428571428555,
			"height": 20,
			"seed": 188851976,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1679752210564,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": {
				"elementId": "bdPmeIdL",
				"focus": -0.2522805639147666,
				"gap": 5.540555681501019
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-21.428571428571445,
					8.571428571428555
				],
				[
					-48.571428571428555,
					-11.428571428571445
				]
			]
		},
		{
			"type": "text",
			"version": 236,
			"versionNonce": 709712648,
			"isDeleted": false,
			"id": "xxSXOi09",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 52.4285714285713,
			"y": -76.71428571428564,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 146.795654296875,
			"height": 25.2,
			"seed": 670746120,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679752210564,
			"link": null,
			"locked": false,
			"fontSize": 21.585760434324026,
			"fontFamily": 1,
			"text": "enqueue(val:t)",
			"rawText": "enqueue(val:t)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "enqueue(val:t)"
		},
		{
			"type": "text",
			"version": 279,
			"versionNonce": 1880078712,
			"isDeleted": false,
			"id": "1EUW6HuR",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 51.42857142857133,
			"y": -44.142857142857,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 195.1327362060547,
			"height": 21.599999999999998,
			"seed": 983622408,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679752210564,
			"link": null,
			"locked": false,
			"fontSize": 18.276286927432384,
			"fontFamily": 1,
			"text": "deque(): T | undefined",
			"rawText": "deque(): T | undefined",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "deque(): T | undefined"
		},
		{
			"type": "text",
			"version": 138,
			"versionNonce": 620542472,
			"isDeleted": false,
			"id": "OjLfjhML",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 117.42857142857136,
			"y": -117.21428571428555,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 40.960968017578125,
			"height": 27.599999999999998,
			"seed": 1035730184,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679752210564,
			"link": null,
			"locked": false,
			"fontSize": 23.428555235606087,
			"fontFamily": 1,
			"text": "O(1)",
			"rawText": "O(1)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "O(1)"
		},
		{
			"type": "text",
			"version": 149,
			"versionNonce": 1103743608,
			"isDeleted": false,
			"id": "LGA2Ypkw",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 118.42854091099323,
			"y": -10.814285714285575,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 50.95184326171875,
			"height": 28.799999999999997,
			"seed": 266638344,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679752210564,
			"link": null,
			"locked": false,
			"fontSize": 24.00752156993456,
			"fontFamily": 1,
			"text": "O(N)",
			"rawText": "O(N)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "O(N)"
		},
		{
			"type": "line",
			"version": 172,
			"versionNonce": 1885878536,
			"isDeleted": false,
			"id": "wXeRe1KnwAmQF8FQA-gDq",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 264.4285714285714,
			"y": -85.21428571428555,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 229,
			"height": 3,
			"seed": 575406088,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1679752210564,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-229,
					-3
				]
			]
		},
		{
			"type": "rectangle",
			"version": 72,
			"versionNonce": 1410972536,
			"isDeleted": false,
			"id": "9iL2N1jnOCAVxDzK6U72g",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -365.27091604194464,
			"y": -333.71764681105094,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 1277.8571428571427,
			"height": 497.8571428571428,
			"seed": 1256085256,
			"groupIds": [],
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1679752210564,
			"link": null,
			"locked": false
		},
		{
			"id": "lKP0Dw6vJGTiF4vNiyZ9d",
			"type": "freedraw",
			"x": -114.34234461337337,
			"y": -189.28907538247955,
			"width": 49,
			"height": 43,
			"angle": 0,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"roundness": null,
			"seed": 1771138056,
			"version": 50,
			"versionNonce": 220362872,
			"isDeleted": true,
			"boundElements": null,
			"updated": 1679752141892,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1,
					0
				],
				[
					4,
					1
				],
				[
					8,
					3
				],
				[
					11,
					5
				],
				[
					15,
					7
				],
				[
					17,
					9
				],
				[
					19,
					12
				],
				[
					20,
					19
				],
				[
					17,
					25
				],
				[
					14,
					30
				],
				[
					12,
					34
				],
				[
					10,
					37
				],
				[
					9,
					38
				],
				[
					8,
					39
				],
				[
					6,
					40
				],
				[
					2,
					41
				],
				[
					-4,
					42
				],
				[
					-8,
					43
				],
				[
					-12,
					43
				],
				[
					-14,
					41
				],
				[
					-18,
					40
				],
				[
					-21,
					37
				],
				[
					-26,
					31
				],
				[
					-28,
					26
				],
				[
					-28,
					22
				],
				[
					-29,
					18
				],
				[
					-29,
					14
				],
				[
					-28,
					11
				],
				[
					-27,
					7
				],
				[
					-25,
					5
				],
				[
					-24,
					3
				],
				[
					-21,
					1
				],
				[
					-18,
					0
				],
				[
					-14,
					0
				],
				[
					-10,
					0
				],
				[
					-5,
					0
				],
				[
					-3,
					0
				],
				[
					-2,
					0
				],
				[
					-1,
					0
				],
				[
					1,
					0
				],
				[
					2,
					0
				],
				[
					4,
					0
				],
				[
					5,
					0
				],
				[
					6,
					0
				],
				[
					0,
					0
				]
			],
			"pressures": [],
			"simulatePressure": true,
			"lastCommittedPoint": [
				6,
				0
			]
		},
		{
			"id": "TEf56W0gchL7qNGkIHhsb",
			"type": "freedraw",
			"x": -334.34234461337337,
			"y": -57.28907538247955,
			"width": 362,
			"height": 115,
			"angle": 0,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"roundness": null,
			"seed": 805136504,
			"version": 105,
			"versionNonce": 649685768,
			"isDeleted": true,
			"boundElements": null,
			"updated": 1679752141892,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					2
				],
				[
					1,
					5
				],
				[
					2,
					13
				],
				[
					4,
					18
				],
				[
					6,
					25
				],
				[
					9,
					34
				],
				[
					20,
					46
				],
				[
					27,
					49
				],
				[
					50,
					57
				],
				[
					68,
					65
				],
				[
					86,
					71
				],
				[
					105,
					76
				],
				[
					165,
					86
				],
				[
					187,
					88
				],
				[
					238,
					93
				],
				[
					249,
					95
				],
				[
					269,
					98
				],
				[
					273,
					98
				],
				[
					277,
					98
				],
				[
					278,
					98
				],
				[
					284,
					98
				],
				[
					286,
					98
				],
				[
					288,
					98
				],
				[
					289,
					98
				],
				[
					290,
					98
				],
				[
					291,
					98
				],
				[
					292,
					98
				],
				[
					293,
					98
				],
				[
					298,
					98
				],
				[
					299,
					98
				],
				[
					302,
					98
				],
				[
					305,
					98
				],
				[
					307,
					98
				],
				[
					311,
					98
				],
				[
					314,
					97
				],
				[
					316,
					97
				],
				[
					319,
					96
				],
				[
					320,
					96
				],
				[
					322,
					96
				],
				[
					325,
					95
				],
				[
					329,
					94
				],
				[
					333,
					90
				],
				[
					334,
					88
				],
				[
					337,
					84
				],
				[
					342,
					78
				],
				[
					348,
					66
				],
				[
					351,
					55
				],
				[
					353,
					41
				],
				[
					353,
					36
				],
				[
					353,
					32
				],
				[
					350,
					26
				],
				[
					349,
					24
				],
				[
					348,
					22
				],
				[
					347,
					21
				],
				[
					345,
					19
				],
				[
					342,
					16
				],
				[
					338,
					12
				],
				[
					322,
					5
				],
				[
					307,
					0
				],
				[
					290,
					-6
				],
				[
					273,
					-9
				],
				[
					259,
					-12
				],
				[
					236,
					-14
				],
				[
					228,
					-16
				],
				[
					196,
					-17
				],
				[
					173,
					-16
				],
				[
					132,
					-14
				],
				[
					101,
					-14
				],
				[
					73,
					-14
				],
				[
					66,
					-13
				],
				[
					65,
					-13
				],
				[
					64,
					-13
				],
				[
					62,
					-13
				],
				[
					58,
					-12
				],
				[
					54,
					-12
				],
				[
					50,
					-11
				],
				[
					44,
					-11
				],
				[
					42,
					-11
				],
				[
					38,
					-11
				],
				[
					32,
					-10
				],
				[
					28,
					-9
				],
				[
					24,
					-9
				],
				[
					22,
					-9
				],
				[
					19,
					-9
				],
				[
					17,
					-9
				],
				[
					16,
					-9
				],
				[
					15,
					-9
				],
				[
					12,
					-8
				],
				[
					10,
					-8
				],
				[
					6,
					-7
				],
				[
					5,
					-7
				],
				[
					2,
					-6
				],
				[
					1,
					-6
				],
				[
					-1,
					-5
				],
				[
					-2,
					-4
				],
				[
					-4,
					-3
				],
				[
					-6,
					-3
				],
				[
					-8,
					-2
				],
				[
					-8,
					-1
				],
				[
					-9,
					-1
				],
				[
					-9,
					-1
				]
			],
			"pressures": [],
			"simulatePressure": true,
			"lastCommittedPoint": [
				-9,
				-1
			]
		},
		{
			"id": "itbQGDJsBUf0CWY_WXvBx",
			"type": "freedraw",
			"x": 52.65765538662663,
			"y": -165.28907538247955,
			"width": 114,
			"height": 13,
			"angle": 0,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"roundness": null,
			"seed": 1317778552,
			"version": 42,
			"versionNonce": 1277995384,
			"isDeleted": true,
			"boundElements": null,
			"updated": 1679752141892,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1,
					0
				],
				[
					4,
					2
				],
				[
					10,
					2
				],
				[
					12,
					3
				],
				[
					18,
					3
				],
				[
					22,
					3
				],
				[
					26,
					3
				],
				[
					30,
					3
				],
				[
					33,
					4
				],
				[
					35,
					4
				],
				[
					40,
					4
				],
				[
					44,
					5
				],
				[
					47,
					5
				],
				[
					56,
					4
				],
				[
					58,
					3
				],
				[
					62,
					2
				],
				[
					66,
					0
				],
				[
					70,
					-1
				],
				[
					74,
					-2
				],
				[
					78,
					-3
				],
				[
					83,
					-4
				],
				[
					86,
					-5
				],
				[
					88,
					-5
				],
				[
					89,
					-5
				],
				[
					90,
					-5
				],
				[
					91,
					-5
				],
				[
					93,
					-6
				],
				[
					95,
					-6
				],
				[
					96,
					-6
				],
				[
					96,
					-7
				],
				[
					97,
					-7
				],
				[
					102,
					-8
				],
				[
					105,
					-8
				],
				[
					107,
					-8
				],
				[
					110,
					-8
				],
				[
					113,
					-8
				],
				[
					114,
					-8
				],
				[
					114,
					-8
				]
			],
			"pressures": [],
			"simulatePressure": true,
			"lastCommittedPoint": [
				114,
				-8
			]
		},
		{
			"id": "mQPU-ofE3sGaONFqYmqwx",
			"type": "freedraw",
			"x": 54.65765538662663,
			"y": -52.28907538247955,
			"width": 32,
			"height": 1,
			"angle": 0,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"roundness": null,
			"seed": 627475208,
			"version": 18,
			"versionNonce": 1499908616,
			"isDeleted": true,
			"boundElements": null,
			"updated": 1679752141892,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1,
					1
				],
				[
					4,
					1
				],
				[
					9,
					1
				],
				[
					13,
					1
				],
				[
					17,
					1
				],
				[
					21,
					1
				],
				[
					24,
					1
				],
				[
					25,
					1
				],
				[
					26,
					1
				],
				[
					27,
					1
				],
				[
					28,
					1
				],
				[
					30,
					1
				],
				[
					32,
					1
				],
				[
					32,
					1
				]
			],
			"pressures": [],
			"simulatePressure": true,
			"lastCommittedPoint": [
				32,
				1
			]
		},
		{
			"id": "I6ue3gIjfAhd7DFDYNkwa",
			"type": "freedraw",
			"x": 83.65765538662663,
			"y": -162.28907538247955,
			"width": 96,
			"height": 3,
			"angle": 0,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"roundness": null,
			"seed": 1816211832,
			"version": 39,
			"versionNonce": 1825094264,
			"isDeleted": true,
			"boundElements": null,
			"updated": 1679752141892,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					2,
					0
				],
				[
					4,
					0
				],
				[
					7,
					1
				],
				[
					8,
					1
				],
				[
					9,
					1
				],
				[
					11,
					1
				],
				[
					15,
					2
				],
				[
					19,
					3
				],
				[
					25,
					3
				],
				[
					29,
					3
				],
				[
					33,
					3
				],
				[
					37,
					3
				],
				[
					42,
					2
				],
				[
					46,
					1
				],
				[
					50,
					1
				],
				[
					51,
					1
				],
				[
					53,
					1
				],
				[
					55,
					1
				],
				[
					57,
					1
				],
				[
					58,
					1
				],
				[
					61,
					1
				],
				[
					62,
					1
				],
				[
					68,
					1
				],
				[
					72,
					1
				],
				[
					76,
					1
				],
				[
					80,
					1
				],
				[
					84,
					1
				],
				[
					85,
					1
				],
				[
					87,
					2
				],
				[
					89,
					2
				],
				[
					91,
					2
				],
				[
					94,
					2
				],
				[
					96,
					2
				],
				[
					96,
					3
				],
				[
					96,
					3
				]
			],
			"pressures": [],
			"simulatePressure": true,
			"lastCommittedPoint": [
				96,
				3
			]
		},
		{
			"id": "rNdGpTQQs0Yn_k5ThUoio",
			"type": "freedraw",
			"x": -119.34234461337337,
			"y": -205.28907538247955,
			"width": 50,
			"height": 46,
			"angle": 0,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"roundness": null,
			"seed": 2134518904,
			"version": 54,
			"versionNonce": 2004766728,
			"isDeleted": true,
			"boundElements": null,
			"updated": 1679752143237,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1,
					0
				],
				[
					1,
					-2
				],
				[
					1,
					-4
				],
				[
					0,
					-7
				],
				[
					-3,
					-11
				],
				[
					-6,
					-16
				],
				[
					-9,
					-20
				],
				[
					-13,
					-24
				],
				[
					-16,
					-26
				],
				[
					-18,
					-27
				],
				[
					-18,
					-28
				],
				[
					-21,
					-28
				],
				[
					-24,
					-26
				],
				[
					-28,
					-20
				],
				[
					-32,
					-13
				],
				[
					-35,
					-6
				],
				[
					-35,
					-2
				],
				[
					-35,
					2
				],
				[
					-35,
					6
				],
				[
					-35,
					10
				],
				[
					-36,
					13
				],
				[
					-36,
					16
				],
				[
					-36,
					17
				],
				[
					-36,
					16
				],
				[
					-37,
					15
				],
				[
					-41,
					11
				],
				[
					-46,
					8
				],
				[
					-48,
					7
				],
				[
					-49,
					7
				],
				[
					-49,
					6
				],
				[
					-49,
					7
				],
				[
					-46,
					10
				],
				[
					-44,
					13
				],
				[
					-43,
					14
				],
				[
					-41,
					15
				],
				[
					-40,
					16
				],
				[
					-38,
					17
				],
				[
					-37,
					17
				],
				[
					-36,
					17
				],
				[
					-35,
					18
				],
				[
					-34,
					17
				],
				[
					-32,
					14
				],
				[
					-30,
					12
				],
				[
					-26,
					9
				],
				[
					-24,
					8
				],
				[
					-20,
					7
				],
				[
					-18,
					7
				],
				[
					-16,
					7
				],
				[
					-15,
					7
				],
				[
					-15,
					7
				]
			],
			"pressures": [],
			"simulatePressure": true,
			"lastCommittedPoint": [
				-15,
				7
			]
		},
		{
			"id": "OhvRlbWQhljpCkNxdDhJA",
			"type": "freedraw",
			"x": -236.34234461337337,
			"y": -84.28907538247955,
			"width": 68,
			"height": 47,
			"angle": 0,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"roundness": null,
			"seed": 702252664,
			"version": 53,
			"versionNonce": 565881720,
			"isDeleted": true,
			"boundElements": null,
			"updated": 1679752141892,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-1,
					0
				],
				[
					-2,
					0
				],
				[
					-3,
					0
				],
				[
					-8,
					1
				],
				[
					-10,
					1
				],
				[
					-15,
					1
				],
				[
					-18,
					2
				],
				[
					-23,
					4
				],
				[
					-27,
					7
				],
				[
					-31,
					11
				],
				[
					-33,
					12
				],
				[
					-37,
					16
				],
				[
					-39,
					18
				],
				[
					-41,
					21
				],
				[
					-43,
					24
				],
				[
					-45,
					27
				],
				[
					-47,
					31
				],
				[
					-49,
					35
				],
				[
					-53,
					39
				],
				[
					-56,
					44
				],
				[
					-58,
					45
				],
				[
					-58,
					46
				],
				[
					-58,
					47
				],
				[
					-58,
					46
				],
				[
					-63,
					39
				],
				[
					-64,
					36
				],
				[
					-65,
					35
				],
				[
					-66,
					32
				],
				[
					-67,
					30
				],
				[
					-67,
					29
				],
				[
					-68,
					30
				],
				[
					-68,
					31
				],
				[
					-66,
					35
				],
				[
					-62,
					41
				],
				[
					-61,
					44
				],
				[
					-60,
					46
				],
				[
					-59,
					46
				],
				[
					-58,
					46
				],
				[
					-54,
					46
				],
				[
					-51,
					46
				],
				[
					-47,
					46
				],
				[
					-44,
					46
				],
				[
					-41,
					46
				],
				[
					-38,
					46
				],
				[
					-33,
					46
				],
				[
					-30,
					46
				],
				[
					-28,
					46
				],
				[
					-26,
					46
				],
				[
					-25,
					46
				],
				[
					-25,
					46
				]
			],
			"pressures": [],
			"simulatePressure": true,
			"lastCommittedPoint": [
				-25,
				46
			]
		},
		{
			"id": "sqq1QUOud9-07bpIy5tgv",
			"type": "freedraw",
			"x": -12.34234461337337,
			"y": -66.28907538247955,
			"width": 45,
			"height": 39,
			"angle": 0,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"roundness": null,
			"seed": 39097464,
			"version": 46,
			"versionNonce": 1360298248,
			"isDeleted": true,
			"boundElements": null,
			"updated": 1679752154438,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-1,
					0
				],
				[
					-2,
					0
				],
				[
					-8,
					0
				],
				[
					-14,
					3
				],
				[
					-19,
					8
				],
				[
					-25,
					14
				],
				[
					-26,
					16
				],
				[
					-28,
					18
				],
				[
					-29,
					20
				],
				[
					-31,
					24
				],
				[
					-31,
					28
				],
				[
					-31,
					32
				],
				[
					-31,
					35
				],
				[
					-31,
					38
				],
				[
					-32,
					38
				],
				[
					-35,
					36
				],
				[
					-38,
					34
				],
				[
					-40,
					32
				],
				[
					-41,
					32
				],
				[
					-41,
					31
				],
				[
					-42,
					31
				],
				[
					-44,
					30
				],
				[
					-45,
					29
				],
				[
					-44,
					29
				],
				[
					-40,
					32
				],
				[
					-38,
					33
				],
				[
					-37,
					34
				],
				[
					-36,
					35
				],
				[
					-35,
					35
				],
				[
					-34,
					36
				],
				[
					-32,
					38
				],
				[
					-30,
					39
				],
				[
					-29,
					39
				],
				[
					-28,
					39
				],
				[
					-27,
					38
				],
				[
					-26,
					37
				],
				[
					-24,
					35
				],
				[
					-20,
					29
				],
				[
					-18,
					26
				],
				[
					-16,
					24
				],
				[
					-14,
					23
				],
				[
					-14,
					22
				],
				[
					-14,
					22
				]
			],
			"pressures": [],
			"simulatePressure": true,
			"lastCommittedPoint": [
				-14,
				22
			]
		},
		{
			"id": "VD_A7_tdYQzuion9vbFu2",
			"type": "freedraw",
			"x": 118.65765538662663,
			"y": -119.28907538247955,
			"width": 75,
			"height": 27,
			"angle": 0,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"roundness": null,
			"seed": 1496707960,
			"version": 84,
			"versionNonce": 1414635272,
			"isDeleted": true,
			"boundElements": null,
			"updated": 1679752159449,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1,
					0
				],
				[
					3,
					0
				],
				[
					4,
					0
				],
				[
					5,
					0
				],
				[
					7,
					0
				],
				[
					8,
					0
				],
				[
					10,
					0
				],
				[
					14,
					0
				],
				[
					16,
					0
				],
				[
					19,
					0
				],
				[
					21,
					0
				],
				[
					24,
					0
				],
				[
					27,
					0
				],
				[
					31,
					0
				],
				[
					34,
					0
				],
				[
					36,
					1
				],
				[
					39,
					1
				],
				[
					41,
					1
				],
				[
					43,
					2
				],
				[
					44,
					2
				],
				[
					45,
					3
				],
				[
					47,
					4
				],
				[
					48,
					4
				],
				[
					50,
					5
				],
				[
					52,
					6
				],
				[
					53,
					7
				],
				[
					54,
					7
				],
				[
					54,
					8
				],
				[
					54,
					9
				],
				[
					54,
					11
				],
				[
					54,
					12
				],
				[
					52,
					14
				],
				[
					49,
					17
				],
				[
					48,
					18
				],
				[
					47,
					18
				],
				[
					45,
					19
				],
				[
					42,
					21
				],
				[
					40,
					22
				],
				[
					38,
					23
				],
				[
					36,
					23
				],
				[
					34,
					23
				],
				[
					30,
					24
				],
				[
					27,
					25
				],
				[
					25,
					25
				],
				[
					22,
					25
				],
				[
					19,
					26
				],
				[
					16,
					26
				],
				[
					13,
					26
				],
				[
					7,
					26
				],
				[
					3,
					26
				],
				[
					-1,
					26
				],
				[
					-3,
					25
				],
				[
					-5,
					25
				],
				[
					-7,
					24
				],
				[
					-9,
					24
				],
				[
					-11,
					23
				],
				[
					-14,
					22
				],
				[
					-16,
					21
				],
				[
					-17,
					20
				],
				[
					-18,
					19
				],
				[
					-20,
					16
				],
				[
					-21,
					12
				],
				[
					-21,
					8
				],
				[
					-21,
					5
				],
				[
					-20,
					4
				],
				[
					-18,
					3
				],
				[
					-16,
					2
				],
				[
					-14,
					1
				],
				[
					-11,
					0
				],
				[
					-10,
					0
				],
				[
					-7,
					-1
				],
				[
					-6,
					-1
				],
				[
					-5,
					-1
				],
				[
					-4,
					-1
				],
				[
					-3,
					-1
				],
				[
					-1,
					-1
				],
				[
					1,
					-1
				],
				[
					2,
					-1
				],
				[
					3,
					-1
				],
				[
					0,
					0
				]
			],
			"pressures": [],
			"simulatePressure": true,
			"lastCommittedPoint": [
				3,
				-1
			]
		},
		{
			"id": "AFDiCPQbVcyZj-DrJ6e9-",
			"type": "freedraw",
			"x": 299.65765538662663,
			"y": -178.28907538247955,
			"width": 205,
			"height": 71,
			"angle": 0,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"roundness": null,
			"seed": 174175608,
			"version": 26,
			"versionNonce": 770906632,
			"isDeleted": true,
			"boundElements": null,
			"updated": 1679752201516,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1,
					0
				],
				[
					3,
					3
				],
				[
					13,
					9
				],
				[
					37,
					23
				],
				[
					55,
					31
				],
				[
					71,
					35
				],
				[
					85,
					41
				],
				[
					94,
					43
				],
				[
					102,
					45
				],
				[
					117,
					45
				],
				[
					128,
					47
				],
				[
					136,
					48
				],
				[
					144,
					49
				],
				[
					153,
					51
				],
				[
					158,
					52
				],
				[
					166,
					54
				],
				[
					172,
					56
				],
				[
					179,
					59
				],
				[
					187,
					63
				],
				[
					195,
					66
				],
				[
					203,
					70
				],
				[
					205,
					71
				],
				[
					205,
					71
				]
			],
			"pressures": [],
			"simulatePressure": true,
			"lastCommittedPoint": [
				205,
				71
			]
		},
		{
			"id": "rwz9cABVSxBpvGZnVBKEz",
			"type": "rectangle",
			"x": 302.65765538662663,
			"y": -169.28907538247955,
			"width": 5,
			"height": 23,
			"angle": 0,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"roundness": {
				"type": 3
			},
			"seed": 837380728,
			"version": 53,
			"versionNonce": 1966038136,
			"isDeleted": true,
			"boundElements": null,
			"updated": 1679752205759,
			"link": null,
			"locked": false
		},
		{
			"id": "o5FFrClOzgBH26RjVOArW",
			"type": "freedraw",
			"x": 303.65765538662663,
			"y": -191.28907538247955,
			"width": 38,
			"height": 30,
			"angle": 0,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"roundness": null,
			"seed": 1029490440,
			"version": 47,
			"versionNonce": 1611388936,
			"isDeleted": true,
			"boundElements": null,
			"updated": 1679752210564,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-1,
					0
				],
				[
					3,
					2
				],
				[
					8,
					5
				],
				[
					13,
					9
				],
				[
					18,
					12
				],
				[
					22,
					15
				],
				[
					26,
					18
				],
				[
					27,
					19
				],
				[
					28,
					21
				],
				[
					29,
					24
				],
				[
					30,
					26
				],
				[
					30,
					28
				],
				[
					31,
					29
				],
				[
					31,
					30
				],
				[
					30,
					30
				],
				[
					28,
					29
				],
				[
					25,
					28
				],
				[
					22,
					26
				],
				[
					16,
					24
				],
				[
					12,
					22
				],
				[
					9,
					20
				],
				[
					7,
					19
				],
				[
					8,
					19
				],
				[
					11,
					20
				],
				[
					17,
					24
				],
				[
					19,
					26
				],
				[
					25,
					29
				],
				[
					27,
					29
				],
				[
					28,
					29
				],
				[
					29,
					29
				],
				[
					31,
					29
				],
				[
					32,
					29
				],
				[
					33,
					29
				],
				[
					34,
					29
				],
				[
					34,
					28
				],
				[
					35,
					26
				],
				[
					35,
					23
				],
				[
					36,
					19
				],
				[
					37,
					17
				],
				[
					37,
					15
				],
				[
					37,
					14
				],
				[
					37,
					13
				],
				[
					37,
					12
				],
				[
					37,
					12
				]
			],
			"pressures": [],
			"simulatePressure": true,
			"lastCommittedPoint": [
				37,
				12
			]
		}
	],
	"appState": {
		"theme": "light",
		"viewBackgroundColor": "#ffffff",
		"currentItemStrokeColor": "#000000",
		"currentItemBackgroundColor": "transparent",
		"currentItemFillStyle": "hachure",
		"currentItemStrokeWidth": 1,
		"currentItemStrokeStyle": "solid",
		"currentItemRoughness": 1,
		"currentItemOpacity": 100,
		"currentItemFontFamily": 1,
		"currentItemFontSize": 16,
		"currentItemTextAlign": "left",
		"currentItemStartArrowhead": null,
		"currentItemEndArrowhead": "arrow",
		"scrollX": 15.34234461337337,
		"scrollY": 326.28907538247955,
		"zoom": {
			"value": 1
		},
		"currentItemRoundness": "round",
		"gridSize": null,
		"colorPalette": {},
		"currentStrokeOptions": null,
		"previousGridSize": null
	},
	"files": {}
}
```
%%