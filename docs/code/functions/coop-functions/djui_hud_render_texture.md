# [djui_hud_render_texture](#djui_hud_render_texture)

|Location|Type|
|-|-|
|[djui_hud_utils.c](https://github.com/abnormalhare/sm64-docs/tree/og-repo/src/pc/djui/djui_hud_utils.c)|Coop Function|

## Decription

Renders a texture to the screen.

## Lua Example

`djui_hud_render_texture(texInfo, x, y, scaleW, scaleH)`

## Parameters

| Field | Type |
| ----- | ---- |
| texInfo | [TextureInfo](structs.md#TextureInfo) |
| x | `float` |
| y | `float` |
| scaleW | `float` |
| scaleH | `float` |

## Return Type

|Type|Description|
|-|-|
|`void`|This function does not return a value.|

## C Prototype

`void djui_hud_render_texture(struct TextureInfo* texInfo, f32 x, f32 y, f32 scaleW, f32 scaleH);`

## [:rewind: Function Index](../functions.md#coop-functions)
