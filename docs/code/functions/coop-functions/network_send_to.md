# [smlua_func_network_send_to](#smlua_func_network_send_to)

|Location|Type|
|-|-|
|[smlua_functions.c](https://github.com/abnormalhare/sm64-docs/tree/og-repo/src/pc/lua/smlua_functions.c)|Coop Function|

## Description

Sends a packet to a particular player (using their local index) containing any data put into `dataTable`.

## Lua Example

`network_send_to(localPlayerIndex, reliable, { data1 = 'hello', data2 = 10 })`

## Parameters

| Field | Type |
| ----- | ---- |
| localPlayerIndex | `integer` |
| reliable | `bool` |
| dataTable | `table` |

> `dataTable` can only contain strings, integers, numbers, booleans, and nil.

> The `reliable` field will ensure that the packet arrives, but should be used sparingly and only when missing a packet would cause a desync.

## Return Type

|Type|Description|
|-|-|
|`bool`|If the function succeeds, it returns `1`. However, if one of the parameters is missing, it returns `0`.|

## [:rewind: Function Index](../functions.md#coop-functions)
