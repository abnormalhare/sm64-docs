# [network_send](#network_send)

|Location|Type|
|-|-|
|[network.c](https://github.com/abnormalhare/sm64-docs/tree/og-repo/src/pc/network/network.c)|Coop Function|

## Description

Sends a packet to all players containing any data put into `dataTable`.

## Lua Example

`network_send(reliable, { data1 = 'hello', data2 = 10 })`

## Parameters

| Field | Type |
| ----- | ---- |
| reliable | `bool` |
| dataTable | `table` |

> `dataTable` can only contain strings, integers, numbers, booleans, and nil.

> The `reliable` field will ensure that the packet arrives, but should be used sparingly and only when missing a packet would cause a desync.

## Return Type

|Type|Description|
|-|-|
|`void`|This function does not return a value.|

## [:rewind: Function Index](../functions.md#coop-functions)
