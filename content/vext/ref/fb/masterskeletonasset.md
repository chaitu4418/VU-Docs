---
title: MasterSkeletonAsset
---

Inherits from [Asset](/vext/ref/fb/asset)

## Summary

### Constructors

|  |
| --- |
| **[MasterSkeletonAsset](#constructor-0)**() |
| **[MasterSkeletonAsset](#constructor-1)**(guid: [Guid](/vext/ref/shared/type/guid)) |
| **[MasterSkeletonAsset](#constructor-2)**(other: [Asset](/vext/ref/fb/asset)) |
| **[MasterSkeletonAsset](#constructor-3)**(other: [DataContainer](/vext/ref/shared/type/datacontainer)) |

### Properties

| Name | Type |
| ---- | ---- |
| {{< prop "masterSkeleton" >}} | [SkeletonAsset](/vext/ref/fb/skeletonasset) \| nil |
| {{< prop "subSkeletons" >}} | [SubSkeleton](/vext/ref/fb/subskeleton)[] |

### Static members

| Name | Type |
| ---- | ---- |
| {{< static "MasterSkeletonAsset" "typeInfo" >}} | [TypeInformation](/vext/ref/shared/type/typeinformation) |

## Constructors

### MasterSkeletonAsset {#constructor-0}

> **MasterSkeletonAsset**()

Creates a new [MasterSkeletonAsset](/vext/ref/fb/masterskeletonasset) frostbite instance.

### MasterSkeletonAsset {#constructor-1}

> **MasterSkeletonAsset**(guid: [Guid](/vext/ref/shared/type/guid))

Creates a new [MasterSkeletonAsset](/vext/ref/fb/masterskeletonasset) frostbite instance and assigns it the provided [Guid](/vext/ref/shared/type/guid).

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **guid** | [Guid](/vext/ref/shared/type/guid) | The [Guid](/vext/ref/shared/type/guid) to assign to the newly created instance. |

### MasterSkeletonAsset {#constructor-2}

> **MasterSkeletonAsset**(other: [Asset](/vext/ref/fb/asset))

Casts an instance of type [Asset](/vext/ref/fb/asset) to [MasterSkeletonAsset](/vext/ref/fb/masterskeletonasset). Will throw an error when trying to cast from an unsupported type.

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **other** | [Asset](/vext/ref/fb/asset) | The instance to cast to [MasterSkeletonAsset](/vext/ref/fb/masterskeletonasset). |

### MasterSkeletonAsset {#constructor-3}

> **MasterSkeletonAsset**(other: [DataContainer](/vext/ref/shared/type/datacontainer))

Casts an instance of type [DataContainer](/vext/ref/shared/type/datacontainer) to [MasterSkeletonAsset](/vext/ref/fb/masterskeletonasset). Will throw an error when trying to cast from an unsupported type.

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **other** | [DataContainer](/vext/ref/shared/type/datacontainer) | The instance to cast to [MasterSkeletonAsset](/vext/ref/fb/masterskeletonasset). |

## Properties

### {{% prop-heading "masterSkeleton" %}}

> **[SkeletonAsset](/vext/ref/fb/skeletonasset)** \| **nil**

### {{% prop-heading "subSkeletons" %}}

> **[SubSkeleton](/vext/ref/fb/subskeleton)**[]

## Static members

### {{% static-heading "typeInfo" %}}

> **[TypeInformation](/vext/ref/shared/type/typeinformation)**

The type information for the [MasterSkeletonAsset](/vext/ref/fb/masterskeletonasset) type.

