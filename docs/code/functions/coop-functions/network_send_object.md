# [network_send_object](#network_send_object)

|Location|Type|
|-|-|
|[packet_object.c](https://github.com/abnormalhare/sm64-docs/tree/og-repo/src/pc/network/packets/packet_object.c)|Coop Function|

## Description

Sends a packet that synchronizes an object. This does not need to be called when `standardSync` is enabled.

## Lua Example

`network_send_object(obj, false)`

## Parameters

| Field | Type |
| ----- | ---- |
| object | [Object](structs.md#Object) |
| reliable | `bool` |

> The `reliable` field will ensure that the packet arrives, but should be used sparingly and only when missing a packet would cause a desync.

## Return Type

|Type|Description|
|-|-|
|`void`|This function does not return a value.|

## [:rewind: Function Index](../functions.md#coop-functions)
