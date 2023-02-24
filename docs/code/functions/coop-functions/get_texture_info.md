# [smlua_func_get_texture_info](#smlua_func_get_texture_info)

|Location|Type|
|-|-|
|[smlua_functions.c](https://github.com/abnormalhare/sm64-docs/tree/og-repo/src/pc/lua/smlua_functions.c)|Coop Function|

## Description

Find any texture in the game by name. Returns the texture with its file size and area.

## Lua Example

`get_texture_info(textureName)`

## Parameters

| Field | Type |
| ----- | ---- |
| textureName | `string` |

## Return Type

|Type|Description|
|-|-|
|[`TextureInfo`](structs.md#TextureInfo)|Returns `{ texture: texture, bitSize: int, width: int, height: int }` unless the parameter is an invalid type or cannot find the texture given.|

## [:rewind: Function Index](../functions.md#coop-functions)
