# [smlua_func_define_custom_obj_fields](#smlua_func_define_custom_obj_fields)

|Location|Type|
|-|-|
|[smlua_cobject.c](https://github.com/abnormalhare/sm64-docs/tree/og-repo/src/pc/lua/smlua_cobject.c)|Coop Function|

## Description

Defines a custom set of overlapping object fields. The function loops through the table given and makes sure to check the given field is valid. It then adds it to a list of custom fields.

## Lua Example

`define_custom_obj_fields({ oCustomField1 = 'u32', oCustomField2 = 's32', oCustomField3 = 'f32' })`

## Parameters

| Field | Type |
| ----- | ---- |
| fieldTable | `Lua Table` |

> ### **Note**
>
> The `fieldTable` table's keys must start with the letter `o` and the values must be either `u32`, `s32`, or `f32`. Otherwise, the function will return `0` and will not add the key to the list of custom functions.

## Return Value

| Type | Description |
|-|-|
bool|If the function does not encounter an error, it returns `1`. However, if the parameter is not a `Lua Table`, the mod it is built into is not currently loading, or the fieldTable's keys are incorrect, it will return `0`.

## [:rewind: Function Index](../../functions.md)
