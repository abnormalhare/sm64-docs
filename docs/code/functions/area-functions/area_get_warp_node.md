# [area_get_warp_node](#area_get_warp_node)

|Location|Type|
|-|-|
|[area.c](https://github.com/abnormalhare/sm64-docs/tree/og-repo/src/game/area.c)|Area Function|

## Description

Loops through the list of the current area's warp nodes. If an area's warp node has the id given, it returns the node with that id.

## Lua Example

`local ObjectWarpNodeValue = area_get_warp_node(id)`

## Parameters

| Field | Type |
| ----- | ---- |
| id | `integer` |

## Returns

|Type|Description|
|-|-|
|[`ObjectWarpNode`](structs.md#ObjectWarpNode)|Returns the node that has the id given or NULL if no node has that id.|

## C Prototype

`struct ObjectWarpNode *area_get_warp_node(u8 id);`

## [:rewind: Function Index](../functions.md#coop-functions)
