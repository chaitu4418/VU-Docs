---
title: MinMaxValueSelectorEntry
---
### Base Classes

[AudioGraphNodePortGroup](AudioGraphNodePortGroup)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                         | Description                                                                                                                             |
| ----------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------- |
| MinMaxValueSelectorEntry()                                                          | Create a new instance of this container type.                                                                                           |
| MinMaxValueSelectorEntry(MinMaxValueSelectorEntry other)                            | Create a reference copy of an instance of the same type.                                                                                |
| MinMaxValueSelectorEntry([AudioGraphNodePortGroup](AudioGraphNodePortGroup) other)  | Upcast an instance of type [AudioGraphNodePortGroup](AudioGraphNodePortGroup) to [MinMaxValueSelectorEntry](MinMaxValueSelectorEntry).  |
| MinMaxValueSelectorEntry([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [MinMaxValueSelectorEntry](MinMaxValueSelectorEntry). |

## Properties

| Name  | Type                                     | Description |
| ----- | ---------------------------------------- | ----------- |
| input | [AudioGraphNodePort](AudioGraphNodePort) |             |

## Methods

| Type                                                 | Name            | Parameters                                     |
| ---------------------------------------------------- | --------------- | ---------------------------------------------- |
| [MinMaxValueSelectorEntry](MinMaxValueSelectorEntry) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [MinMaxValueSelectorEntry](MinMaxValueSelectorEntry) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |