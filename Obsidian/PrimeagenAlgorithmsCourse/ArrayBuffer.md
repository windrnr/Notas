---

excalidraw-plugin: parsed
tags: [excalidraw]

---
==⚠  Switch to EXCALIDRAW VIEW in the MORE OPTIONS menu of this document. ⚠==


# Text Elements
[                ] ^6XBJEbuH

h ^ASVjoVED

t ^BxQxvMG7

null ^BZk3FT8C

null ^4gznZEuH

0 ^BcaR36Nf

N ^L0SM6L5f

[ ^0APGeopo

] ^4Xdl0qrI

We have something like an Array List with Array like storage with the difference
that we are not using 0 as our head and length as our tail, instead, we have a
index-based head and tail, and everything between are the items we have.

If you want to remove from the front, you can + 1 to the head and do the operation
on it, and now we have a new head, same thing with tail.

If we push tail pass the edge, we can use the modulo operator to get the index into
the array, connecting the array. ^caDo6KAN

+1 ^ZvjgMkqN

+1 ^aUWOBPhf

this.tail % len ^BCo9aTwE

An inherit trait of RingBuffers is that they maintain order, so when we shift or un-shift
we get the last or first element added to the array. ^J3rW3q8N

If the tail exceeds the head, we will have to resize. In order to do so we would have
to start on the head, go the length and write that into a larger capacity buffer.
This way you would have it in the correct order with the head at 0 and the tail at length.  ^eyRyroWX

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
			"version": 101,
			"versionNonce": 1635213688,
			"isDeleted": false,
			"id": "6XBJEbuH",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -189,
			"y": -135.5,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 367.0865478515625,
			"height": 48,
			"seed": 754320392,
			"groupIds": [],
			"roundness": null,
			"boundElements": [
				{
					"id": "yr-tH1wQPAip-Og2pphZr",
					"type": "arrow"
				}
			],
			"updated": 1679698668893,
			"link": null,
			"locked": false,
			"fontSize": 40.83333333333331,
			"fontFamily": 1,
			"text": "[                ]",
			"rawText": "[                ]",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "[                ]"
		},
		{
			"type": "text",
			"version": 97,
			"versionNonce": 490967560,
			"isDeleted": false,
			"id": "ASVjoVED",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -86,
			"y": -26.5,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 18.702560424804688,
			"height": 44.4,
			"seed": 191835400,
			"groupIds": [],
			"roundness": null,
			"boundElements": [
				{
					"id": "uuepAsVeLMhkGHXT9ZO_K",
					"type": "arrow"
				}
			],
			"updated": 1679698668893,
			"link": null,
			"locked": false,
			"fontSize": 37.86440435833482,
			"fontFamily": 1,
			"text": "h",
			"rawText": "h",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "h"
		},
		{
			"type": "text",
			"version": 158,
			"versionNonce": 2013033080,
			"isDeleted": false,
			"id": "BxQxvMG7",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 49,
			"y": -16.5,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 15.75823974609375,
			"height": 32.4,
			"seed": 213748488,
			"groupIds": [],
			"roundness": null,
			"boundElements": [
				{
					"id": "FrXrLtZx6PMLCRD0iFUdr",
					"type": "arrow"
				}
			],
			"updated": 1679698668893,
			"link": null,
			"locked": false,
			"fontSize": 27.905627663539292,
			"fontFamily": 1,
			"text": "t",
			"rawText": "t",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "t"
		},
		{
			"type": "arrow",
			"version": 597,
			"versionNonce": 1779699976,
			"isDeleted": false,
			"id": "uuepAsVeLMhkGHXT9ZO_K",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "dotted",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -76.27189997122412,
			"y": -33.91512206002272,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 1.2677102681041674,
			"height": 44.386834557670944,
			"seed": 2081293944,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1679698668893,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "ASVjoVED",
				"focus": 0.1620414961829039,
				"gap": 7.415122060022711
			},
			"endBinding": {
				"elementId": "0APGeopo",
				"focus": 0.27970225951582905,
				"gap": 1.8701174449855102
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
					-1.2677102681041674,
					-44.386834557670944
				]
			]
		},
		{
			"type": "arrow",
			"version": 345,
			"versionNonce": 2109170552,
			"isDeleted": false,
			"id": "FrXrLtZx6PMLCRD0iFUdr",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "dotted",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 56.93431353090796,
			"y": -24.5,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0.9195728434580843,
			"height": 54.59995971673537,
			"seed": 652025864,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1679698668893,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "BxQxvMG7",
				"focus": 0.05911046091446645,
				"gap": 8
			},
			"endBinding": {
				"elementId": "4Xdl0qrI",
				"focus": -0.18826144206825982,
				"gap": 2.0000000000000284
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
					-0.9195728434580843,
					-54.59995971673537
				]
			]
		},
		{
			"type": "arrow",
			"version": 106,
			"versionNonce": 1719447560,
			"isDeleted": false,
			"id": "WbG89Sjl7v_L59mJlUOcC",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "dotted",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 78,
			"y": -113.5,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 66,
			"height": 0,
			"seed": 1305324408,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1679698668893,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "BZk3FT8C",
				"focus": 2.0833333333333335,
				"gap": 13
			},
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
					66,
					0
				]
			]
		},
		{
			"type": "arrow",
			"version": 223,
			"versionNonce": 1357657208,
			"isDeleted": false,
			"id": "AYbwKyF4HZboY2fmflxOo",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "dotted",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -97,
			"y": -118.10230053477531,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 64,
			"height": 0.6023005347753099,
			"seed": 38644856,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1679698668893,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "0APGeopo",
				"focus": 0.42861034683349336,
				"gap": 11
			},
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
					-64,
					0.6023005347753099
				]
			]
		},
		{
			"type": "text",
			"version": 50,
			"versionNonce": 712601352,
			"isDeleted": false,
			"id": "BZk3FT8C",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "dotted",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 88,
			"y": -150.5,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 31.219970703125,
			"height": 24,
			"seed": 2072970872,
			"groupIds": [],
			"roundness": null,
			"boundElements": [
				{
					"id": "WbG89Sjl7v_L59mJlUOcC",
					"type": "arrow"
				}
			],
			"updated": 1679698668893,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "null",
			"rawText": "null",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "null"
		},
		{
			"type": "text",
			"version": 53,
			"versionNonce": 1734272376,
			"isDeleted": false,
			"id": "4gznZEuH",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "dotted",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -140.6099853515625,
			"y": -158.5,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 31.219970703125,
			"height": 24,
			"seed": 1803155720,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679698668894,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "null",
			"rawText": "null",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "null"
		},
		{
			"type": "text",
			"version": 55,
			"versionNonce": 1854295560,
			"isDeleted": false,
			"id": "BcaR36Nf",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "dotted",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -187,
			"y": -87.5,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 13.759994506835938,
			"height": 24,
			"seed": 442146680,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679698668894,
			"link": null,
			"locked": false,
			"fontSize": 20,
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
			"version": 107,
			"versionNonce": 1582528120,
			"isDeleted": false,
			"id": "L0SM6L5f",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "dotted",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 158.12000274658203,
			"y": -85.5,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 12.879989624023438,
			"height": 24,
			"seed": 1181697656,
			"groupIds": [],
			"roundness": null,
			"boundElements": [
				{
					"id": "yr-tH1wQPAip-Og2pphZr",
					"type": "arrow"
				}
			],
			"updated": 1679698668894,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "N",
			"rawText": "N",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "N"
		},
		{
			"type": "text",
			"version": 176,
			"versionNonce": 2074037512,
			"isDeleted": false,
			"id": "0APGeopo",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "dotted",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -86,
			"y": -133.5,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 21.8111572265625,
			"height": 52.8,
			"seed": 1648386680,
			"groupIds": [],
			"roundness": null,
			"boundElements": [
				{
					"id": "uuepAsVeLMhkGHXT9ZO_K",
					"type": "arrow"
				},
				{
					"id": "AYbwKyF4HZboY2fmflxOo",
					"type": "arrow"
				}
			],
			"updated": 1679698668894,
			"link": null,
			"locked": false,
			"fontSize": 44.43993828110069,
			"fontFamily": 1,
			"text": "[",
			"rawText": "[",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "["
		},
		{
			"type": "text",
			"version": 95,
			"versionNonce": 177071992,
			"isDeleted": false,
			"id": "4Xdl0qrI",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "dotted",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 43,
			"y": -131.5,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 21.000030517578125,
			"height": 50.4,
			"seed": 1074689400,
			"groupIds": [],
			"roundness": null,
			"boundElements": [
				{
					"id": "FrXrLtZx6PMLCRD0iFUdr",
					"type": "arrow"
				}
			],
			"updated": 1679698668894,
			"link": null,
			"locked": false,
			"fontSize": 42.000033569387156,
			"fontFamily": 1,
			"text": "]",
			"rawText": "]",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "]"
		},
		{
			"type": "text",
			"version": 663,
			"versionNonce": 457206792,
			"isDeleted": false,
			"id": "caDo6KAN",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "dotted",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -243,
			"y": 34.5,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 856.0791015625,
			"height": 216,
			"seed": 150114936,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679698668894,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "We have something like an Array List with Array like storage with the difference\nthat we are not using 0 as our head and length as our tail, instead, we have a\nindex-based head and tail, and everything between are the items we have.\n\nIf you want to remove from the front, you can + 1 to the head and do the operation\non it, and now we have a new head, same thing with tail.\n\nIf we push tail pass the edge, we can use the modulo operator to get the index into\nthe array, connecting the array.",
			"rawText": "We have something like an Array List with Array like storage with the difference\nthat we are not using 0 as our head and length as our tail, instead, we have a\nindex-based head and tail, and everything between are the items we have.\n\nIf you want to remove from the front, you can + 1 to the head and do the operation\non it, and now we have a new head, same thing with tail.\n\nIf we push tail pass the edge, we can use the modulo operator to get the index into\nthe array, connecting the array.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "We have something like an Array List with Array like storage with the difference\nthat we are not using 0 as our head and length as our tail, instead, we have a\nindex-based head and tail, and everything between are the items we have.\n\nIf you want to remove from the front, you can + 1 to the head and do the operation\non it, and now we have a new head, same thing with tail.\n\nIf we push tail pass the edge, we can use the modulo operator to get the index into\nthe array, connecting the array."
		},
		{
			"type": "arrow",
			"version": 36,
			"versionNonce": 139606136,
			"isDeleted": false,
			"id": "Kk3XiVWDseYvHRET_D8dq",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "dotted",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 174,
			"y": 56.5,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 0,
			"seed": 1579379464,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1679698668894,
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
					0,
					0
				]
			]
		},
		{
			"type": "rectangle",
			"version": 41,
			"versionNonce": 124103432,
			"isDeleted": false,
			"id": "aGxwcYTWDaJw-I-sw4y7v",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "dotted",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -59,
			"y": -130.5,
			"strokeColor": "#1864ab",
			"backgroundColor": "transparent",
			"width": 26,
			"height": 37,
			"seed": 1012237832,
			"groupIds": [],
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "NapOxv-1p-cXStU9pFVFJ",
					"type": "arrow"
				}
			],
			"updated": 1679698668894,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 71,
			"versionNonce": 1264871800,
			"isDeleted": false,
			"id": "brJ46RGOYu_GVSD1XT4B-",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "dotted",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 69,
			"y": -129,
			"strokeColor": "#1864ab",
			"backgroundColor": "transparent",
			"width": 26,
			"height": 37,
			"seed": 1122123128,
			"groupIds": [],
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "alLXHw21HIat4oUHm-azB",
					"type": "arrow"
				},
				{
					"id": "yr-tH1wQPAip-Og2pphZr",
					"type": "arrow"
				}
			],
			"updated": 1679698668894,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 49,
			"versionNonce": 1519061512,
			"isDeleted": false,
			"id": "ZvjgMkqN",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "dotted",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 69,
			"y": -14.5,
			"strokeColor": "#1864ab",
			"backgroundColor": "transparent",
			"width": 17.91998291015625,
			"height": 24,
			"seed": 1945914744,
			"groupIds": [],
			"roundness": null,
			"boundElements": [
				{
					"id": "alLXHw21HIat4oUHm-azB",
					"type": "arrow"
				}
			],
			"updated": 1679698668894,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "+1",
			"rawText": "+1",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "+1"
		},
		{
			"type": "text",
			"version": 62,
			"versionNonce": 789084792,
			"isDeleted": false,
			"id": "aUWOBPhf",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "dotted",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -60.959991455078125,
			"y": -13.5,
			"strokeColor": "#1864ab",
			"backgroundColor": "transparent",
			"width": 17.91998291015625,
			"height": 24,
			"seed": 824673288,
			"groupIds": [],
			"roundness": null,
			"boundElements": [
				{
					"id": "NapOxv-1p-cXStU9pFVFJ",
					"type": "arrow"
				}
			],
			"updated": 1679698668894,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "+1",
			"rawText": "+1",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "+1"
		},
		{
			"type": "arrow",
			"version": 80,
			"versionNonce": 2142013704,
			"isDeleted": false,
			"id": "NapOxv-1p-cXStU9pFVFJ",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "dotted",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -47,
			"y": -24.5,
			"strokeColor": "#1864ab",
			"backgroundColor": "transparent",
			"width": 1,
			"height": 63,
			"seed": 1532031496,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1679698668894,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "aUWOBPhf",
				"focus": 0.5065228154948426,
				"gap": 11
			},
			"endBinding": {
				"elementId": "aGxwcYTWDaJw-I-sw4y7v",
				"focus": -0.029253731343283577,
				"gap": 6
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
					1,
					-63
				]
			]
		},
		{
			"type": "arrow",
			"version": 47,
			"versionNonce": 100821880,
			"isDeleted": false,
			"id": "alLXHw21HIat4oUHm-azB",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "dotted",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 81,
			"y": -23.5,
			"strokeColor": "#1864ab",
			"backgroundColor": "transparent",
			"width": 3,
			"height": 65,
			"seed": 2054327560,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1679698668894,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "ZvjgMkqN",
				"focus": 0.21765956712868959,
				"gap": 9
			},
			"endBinding": {
				"elementId": "brJ46RGOYu_GVSD1XT4B-",
				"focus": -0.21765685730149917,
				"gap": 3.5
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
					-65
				]
			]
		},
		{
			"type": "text",
			"version": 60,
			"versionNonce": 714488952,
			"isDeleted": false,
			"id": "BCo9aTwE",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "dotted",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 130,
			"y": -38.5,
			"strokeColor": "#1864ab",
			"backgroundColor": "transparent",
			"width": 140.4998321533203,
			"height": 24,
			"seed": 2057198456,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679698668894,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "this.tail % len",
			"rawText": "this.tail % len",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "this.tail % len"
		},
		{
			"type": "arrow",
			"version": 1275,
			"versionNonce": 243789176,
			"isDeleted": false,
			"id": "yr-tH1wQPAip-Og2pphZr",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 178,
			"y": -93.5,
			"strokeColor": "#1864ab",
			"backgroundColor": "transparent",
			"width": 446,
			"height": 77,
			"seed": 1439454984,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1679698668894,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "L0SM6L5f",
				"focus": -1.469236675223046,
				"gap": 8
			},
			"endBinding": {
				"elementId": "6XBJEbuH",
				"focus": -0.9537301644300552,
				"gap": 10
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
					29,
					-3
				],
				[
					-2,
					-76
				],
				[
					-417,
					-77
				],
				[
					-377,
					-21
				]
			]
		},
		{
			"type": "text",
			"version": 227,
			"versionNonce": 1884407304,
			"isDeleted": false,
			"id": "J3rW3q8N",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -248,
			"y": 281.5,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 878.6990966796875,
			"height": 48,
			"seed": 2046083080,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679698668894,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "An inherit trait of RingBuffers is that they maintain order, so when we shift or un-shift\nwe get the last or first element added to the array.",
			"rawText": "An inherit trait of RingBuffers is that they maintain order, so when we shift or un-shift\nwe get the last or first element added to the array.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "An inherit trait of RingBuffers is that they maintain order, so when we shift or un-shift\nwe get the last or first element added to the array."
		},
		{
			"type": "text",
			"version": 387,
			"versionNonce": 1260093048,
			"isDeleted": false,
			"id": "eyRyroWX",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -238,
			"y": 362.5,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 927.63916015625,
			"height": 72,
			"seed": 1872228728,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679698668894,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "If the tail exceeds the head, we will have to resize. In order to do so we would have\nto start on the head, go the length and write that into a larger capacity buffer.\nThis way you would have it in the correct order with the head at 0 and the tail at length. ",
			"rawText": "If the tail exceeds the head, we will have to resize. In order to do so we would have\nto start on the head, go the length and write that into a larger capacity buffer.\nThis way you would have it in the correct order with the head at 0 and the tail at length. ",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "If the tail exceeds the head, we will have to resize. In order to do so we would have\nto start on the head, go the length and write that into a larger capacity buffer.\nThis way you would have it in the correct order with the head at 0 and the tail at length. "
		},
		{
			"id": "VmfV8CShyXLCP7lKcJBGe",
			"type": "rectangle",
			"x": -285.2133132420403,
			"y": -204.09190055012172,
			"width": 989.2307692307693,
			"height": 653.0769230769231,
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
			"seed": 913298696,
			"version": 66,
			"versionNonce": 149544824,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1679709806499,
			"link": null,
			"locked": false
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
		"currentItemFontSize": 20,
		"currentItemTextAlign": "left",
		"currentItemStartArrowhead": null,
		"currentItemEndArrowhead": "arrow",
		"scrollX": 504.44408247280955,
		"scrollY": 260.2457467039679,
		"zoom": {
			"value": 1.2999999999999998
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