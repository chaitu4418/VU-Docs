---
title: RagdollAsset
---

Inherits from [Asset](/vext/ref/fb/asset)

## Summary

### Constructors

|  |
| --- |
| **[RagdollAsset](#constructor-0)**() |
| **[RagdollAsset](#constructor-1)**(guid: [Guid](/vext/ref/shared/type/guid)) |
| **[RagdollAsset](#constructor-2)**(other: [Asset](/vext/ref/fb/asset)) |
| **[RagdollAsset](#constructor-3)**(other: [DataContainer](/vext/ref/shared/type/datacontainer)) |

### Properties

| Name | Type |
| ---- | ---- |
| {{< prop "materialPair" >}} | [MaterialContainerPair](/vext/ref/fb/materialcontainerpair) \| nil |
| {{< prop "useServerRagdoll" >}} | bool |

### Static members

| Name | Type |
| ---- | ---- |
| {{< static "RagdollAsset" "typeInfo" >}} | [TypeInformation](/vext/ref/shared/type/typeinformation) |

## Constructors

### RagdollAsset {#constructor-0}

> **RagdollAsset**()

Creates a new [RagdollAsset](/vext/ref/fb/ragdollasset) frostbite instance.

### RagdollAsset {#constructor-1}

> **RagdollAsset**(guid: [Guid](/vext/ref/shared/type/guid))

Creates a new [RagdollAsset](/vext/ref/fb/ragdollasset) frostbite instance and assigns it the provided [Guid](/vext/ref/shared/type/guid).

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **guid** | [Guid](/vext/ref/shared/type/guid) | The [Guid](/vext/ref/shared/type/guid) to assign to the newly created instance. |

### RagdollAsset {#constructor-2}

> **RagdollAsset**(other: [Asset](/vext/ref/fb/asset))

Casts an instance of type [Asset](/vext/ref/fb/asset) to [RagdollAsset](/vext/ref/fb/ragdollasset). Will throw an error when trying to cast from an unsupported type.

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **other** | [Asset](/vext/ref/fb/asset) | The instance to cast to [RagdollAsset](/vext/ref/fb/ragdollasset). |

### RagdollAsset {#constructor-3}

> **RagdollAsset**(other: [DataContainer](/vext/ref/shared/type/datacontainer))

Casts an instance of type [DataContainer](/vext/ref/shared/type/datacontainer) to [RagdollAsset](/vext/ref/fb/ragdollasset). Will throw an error when trying to cast from an unsupported type.

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **other** | [DataContainer](/vext/ref/shared/type/datacontainer) | The instance to cast to [RagdollAsset](/vext/ref/fb/ragdollasset). |

## Properties

### {{% prop-heading "materialPair" %}}

> **[MaterialContainerPair](/vext/ref/fb/materialcontainerpair)** \| **nil**

### {{% prop-heading "useServerRagdoll" %}}

> **bool**

## Static members

### {{% static-heading "typeInfo" %}}

> **[TypeInformation](/vext/ref/shared/type/typeinformation)**

The type information for the [RagdollAsset](/vext/ref/fb/ragdollasset) type.

