---
title: PlatformSplitterEntityData
---
### Base Classes

[EntityData](EntityData)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                           | Description                                                                                                                                 |
| ------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- |
| PlatformSplitterEntityData()                                                          | Create a new instance of this container type.                                                                                               |
| PlatformSplitterEntityData(PlatformSplitterEntityData other)                          | Create a reference copy of an instance of the same type.                                                                                    |
| PlatformSplitterEntityData([EntityData](EntityData) other)                            | Upcast an instance of type [EntityData](EntityData) to [PlatformSplitterEntityData](PlatformSplitterEntityData).                            |
| PlatformSplitterEntityData([GameObjectData](GameObjectData) other)                    | Upcast an instance of type [GameObjectData](GameObjectData) to [PlatformSplitterEntityData](PlatformSplitterEntityData).                    |
| PlatformSplitterEntityData([GameDataContainer](GameDataContainer) other)              | Upcast an instance of type [GameDataContainer](GameDataContainer) to [PlatformSplitterEntityData](PlatformSplitterEntityData).              |
| PlatformSplitterEntityData([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [PlatformSplitterEntityData](PlatformSplitterEntityData). |

## Properties

| Name    | Type           | Description |
| ------- | -------------- | ----------- |
| realm   | [Realm](Realm) |             |
| runOnce | bool           |             |

## Methods

| Type                                                     | Name            | Parameters                                     |
| -------------------------------------------------------- | --------------- | ---------------------------------------------- |
| [PlatformSplitterEntityData](PlatformSplitterEntityData) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [PlatformSplitterEntityData](PlatformSplitterEntityData) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |