---
title: BasicUnlockInfo
---

## Summary

### Constructors

|  |
| --- |
| **[BasicUnlockInfo](#constructor-0)**() |
| **[BasicUnlockInfo](#constructor-1)**(guid: [Guid](/vext/ref/shared/type/guid)) |

### Properties

| Name | Type |
| ---- | ---- |
| {{< prop "unlockGuid" >}} | [Guid](/vext/ref/shared/type/guid) |
| {{< prop "identifier" >}} | int |
| {{< prop "unlockScore" >}} | int |
| {{< prop "licenses" >}} | string[] |
| {{< prop "additionalLicenses" >}} | string[] |
| {{< prop "stringId" >}} | string |

### Methods

| Method | Returns |
| ------ | ------- |
| **[Clone](#clone)**() | [BasicUnlockInfo](/vext/ref/fb/basicunlockinfo) |

### Static members

| Name | Type |
| ---- | ---- |
| {{< static "BasicUnlockInfo" "typeInfo" >}} | [TypeInformation](/vext/ref/shared/type/typeinformation) |

## Constructors

### BasicUnlockInfo {#constructor-0}

> **BasicUnlockInfo**()

Creates a new [BasicUnlockInfo](/vext/ref/fb/basicunlockinfo) frostbite instance.

### BasicUnlockInfo {#constructor-1}

> **BasicUnlockInfo**(guid: [Guid](/vext/ref/shared/type/guid))

Creates a new [BasicUnlockInfo](/vext/ref/fb/basicunlockinfo) frostbite instance and assigns it the provided [Guid](/vext/ref/shared/type/guid).

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **guid** | [Guid](/vext/ref/shared/type/guid) | The [Guid](/vext/ref/shared/type/guid) to assign to the newly created instance. |

## Properties

### {{% prop-heading "unlockGuid" %}}

> **[Guid](/vext/ref/shared/type/guid)**

### {{% prop-heading "identifier" %}}

> **int**

### {{% prop-heading "unlockScore" %}}

> **int**

### {{% prop-heading "licenses" %}}

> **string**[]

### {{% prop-heading "additionalLicenses" %}}

> **string**[]

### {{% prop-heading "stringId" %}}

> **string**

## Methods

### Clone {#clone}

> **Clone**(): [BasicUnlockInfo](/vext/ref/fb/basicunlockinfo)

Creates a shallow-copy clone of this structure, which is essentially the equivalent of creating a new structure of the same type and assigning the values of this structure to all of its properties. Any properties that contain structure types (eg. [Vec3](/vext/ref/shared/type/vec3)) will be cloned when assigning, while properties that contain instance types (eg. [DataContainer](/vext/ref/shared/type/datacontainer)) will be referencing the same instance.

#### Returns

| Type | Description |
| ---- | ----------- |
| **[BasicUnlockInfo](/vext/ref/fb/basicunlockinfo)** | The newly created structure. |

## Static members

### {{% static-heading "typeInfo" %}}

> **[TypeInformation](/vext/ref/shared/type/typeinformation)**

The type information for the [BasicUnlockInfo](/vext/ref/fb/basicunlockinfo) type.

