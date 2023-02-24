# [djui_hud_render_texture_interpolated](#djui_hud_render_texture_interpolated)

|Location|Type|
|-|-|
|[djui_hud_utils.c](https://github.com/abnormalhare/sm64-docs/tree/og-repo/src/pc/djui/djui_hud_utils.c)|Coop Function|

## Description

Renders an interpolated texture to the screen.

## Lua Example

`djui_hud_render_texture_interpolated(texInfo, prevX, prevY, prevScaleW, prevScaleH, x, y, scaleW, scaleH)`

## Parameters

| Field | Type |
| ----- | ---- |
| texInfo | [TextureInfo](structs.md#TextureInfo) |
| prevX | `float` |
| prevY | `float` |
| prevScaleW | `float` |
| prevScaleH | `float` |
| x | `float` |
| y | `float` |
| scaleW | `float` |
| scaleH | `float` |

## Return Type

|Type|Description|
|-|-|
|`void`|This function does not return a value.|

## C Prototype

`void djui_hud_render_texture_interpolated(struct TextureInfo* texInfo, f32 prevX, f32 prevY, f32 prevScaleW, f32 prevScaleH, f32 x, f32 y, f32 scaleW, f32 scaleH);`

## [:rewind: Function Index](../functions.md#coop-functions)
