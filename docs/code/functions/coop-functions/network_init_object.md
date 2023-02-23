# [smlua_func_network_init_object](#smlua_func_network_init_object)

|Location|Type|
|-|-|
|[smlua_functions.c](https://github.com/abnormalhare/sm64-docs/tree/og-repo/src/pc/lua/smlua_cfunctions.c)|Coop Function|

## Description

Enables synchronization on an object. The function initializes syncing on the object. If the 3rd parameter is a table, it assigns the given fields to it.

> Setting `standardSync` to `true` will automatically synchronize the object at a rate that is determined based on player distance. The commonly used object fields will be automatically synchronized.  
>
> Setting `standardSync` to `false` will not automatically synchronize the object, or add commonly used object fields. The mod must manually call `network_send_object()` when fields have changed.

The `fieldTable` parameter can be `nil`, or a list of object fields.

## Lua Example

`network_init_object(obj, true, { 'oCustomField1', 'oCustomField2', 'oCustomField3' })`

## Parameters

| Field | Type |
| ----- | ---- |
| object | [Object](../../structs.md#Object) |
| standardSync | `bool` |
| fieldTable | `Lua Table` |

## Return Type

|Type|Description|
|-|-|
| `bool` |If the function does not encounter an error, it returns `1`. However, If any parameter is not its intended value or the object it attempts to sync does not sync, it returns `0` |

## [:rewind: Function Index](../../functions.md#coop-functions)
