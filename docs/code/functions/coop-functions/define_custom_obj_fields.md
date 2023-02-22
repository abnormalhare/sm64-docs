# [define_custom_obj_fields](#define_custom_obj_fields)

## Description

<div style="float: right; background-color: rgba(0, 0, 0, 0.2);padding: 5px; border: solid; border-color: #000; color: #ffff00;">
    
|Location|
|-|
|Row 1, Column 1|

    
</div>

Defines a custom set of overlapping object fields. Lorem ipsum dolor yo mamaLorem ipsum dolor yo mamaLorem ipsum dolor yo mamaLorem ipsum dolor yo mamaLorem ipsum dolor yo mamaLorem ipsum dolor yo mamaLorem ipsum dolor yo mama

## Lua Example

`define_custom_obj_fields({ oCustomField1 = 'u32', oCustomField2 = 's32', oCustomField3 = 'f32' })`

## Parameters

| Field | Type |
| ----- | ---- |
| fieldTable | `Lua Table` |

> ## Note
>
> The `fieldTable` table's keys must start with the letter `o` and the values must be either `u32`, `s32`, or `f32`.

## C Prototype

`N/A`

## [:rewind: Function Index](../../functions.md)