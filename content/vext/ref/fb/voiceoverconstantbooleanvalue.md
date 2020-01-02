---
title: VoiceOverConstantBooleanValue
---
### Base Classes

[VoiceOverConstantValue](VoiceOverConstantValue)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                              | Description                                                                                                                                       |
| ---------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------- |
| VoiceOverConstantBooleanValue()                                                          | Create a new instance of this container type.                                                                                                     |
| VoiceOverConstantBooleanValue(VoiceOverConstantBooleanValue other)                       | Create a reference copy of an instance of the same type.                                                                                          |
| VoiceOverConstantBooleanValue([VoiceOverConstantValue](VoiceOverConstantValue) other)    | Upcast an instance of type [VoiceOverConstantValue](VoiceOverConstantValue) to [VoiceOverConstantBooleanValue](VoiceOverConstantBooleanValue).    |
| VoiceOverConstantBooleanValue([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [VoiceOverConstantBooleanValue](VoiceOverConstantBooleanValue). |

## Properties

| Name  | Type | Description |
| ----- | ---- | ----------- |
| value | bool |             |

## Methods

| Type                                                           | Name            | Parameters                                     |
| -------------------------------------------------------------- | --------------- | ---------------------------------------------- |
| [VoiceOverConstantBooleanValue](VoiceOverConstantBooleanValue) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [VoiceOverConstantBooleanValue](VoiceOverConstantBooleanValue) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |