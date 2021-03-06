---
title: TransformPropertyTrackData
---

Inherits from [SimplePropertyTrackData](/vext/ref/fb/simplepropertytrackdata)

## Summary

### Constructors

|  |
| --- |
| **[TransformPropertyTrackData](#constructor-0)**() |
| **[TransformPropertyTrackData](#constructor-1)**(guid: [Guid](/vext/ref/shared/type/guid)) |
| **[TransformPropertyTrackData](#constructor-2)**(other: [SimplePropertyTrackData](/vext/ref/fb/simplepropertytrackdata)) |
| **[TransformPropertyTrackData](#constructor-3)**(other: [PropertyTrackData](/vext/ref/fb/propertytrackdata)) |
| **[TransformPropertyTrackData](#constructor-4)**(other: [DataContainer](/vext/ref/shared/type/datacontainer)) |

### Properties

| Name | Type |
| ---- | ---- |
| {{< prop "values" >}} | [LinearTransform](/vext/ref/shared/type/lineartransform)[] |

### Static members

| Name | Type |
| ---- | ---- |
| {{< static "TransformPropertyTrackData" "typeInfo" >}} | [TypeInformation](/vext/ref/shared/type/typeinformation) |

## Constructors

### TransformPropertyTrackData {#constructor-0}

> **TransformPropertyTrackData**()

Creates a new [TransformPropertyTrackData](/vext/ref/fb/transformpropertytrackdata) frostbite instance.

### TransformPropertyTrackData {#constructor-1}

> **TransformPropertyTrackData**(guid: [Guid](/vext/ref/shared/type/guid))

Creates a new [TransformPropertyTrackData](/vext/ref/fb/transformpropertytrackdata) frostbite instance and assigns it the provided [Guid](/vext/ref/shared/type/guid).

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **guid** | [Guid](/vext/ref/shared/type/guid) | The [Guid](/vext/ref/shared/type/guid) to assign to the newly created instance. |

### TransformPropertyTrackData {#constructor-2}

> **TransformPropertyTrackData**(other: [SimplePropertyTrackData](/vext/ref/fb/simplepropertytrackdata))

Casts an instance of type [SimplePropertyTrackData](/vext/ref/fb/simplepropertytrackdata) to [TransformPropertyTrackData](/vext/ref/fb/transformpropertytrackdata). Will throw an error when trying to cast from an unsupported type.

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **other** | [SimplePropertyTrackData](/vext/ref/fb/simplepropertytrackdata) | The instance to cast to [TransformPropertyTrackData](/vext/ref/fb/transformpropertytrackdata). |

### TransformPropertyTrackData {#constructor-3}

> **TransformPropertyTrackData**(other: [PropertyTrackData](/vext/ref/fb/propertytrackdata))

Casts an instance of type [PropertyTrackData](/vext/ref/fb/propertytrackdata) to [TransformPropertyTrackData](/vext/ref/fb/transformpropertytrackdata). Will throw an error when trying to cast from an unsupported type.

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **other** | [PropertyTrackData](/vext/ref/fb/propertytrackdata) | The instance to cast to [TransformPropertyTrackData](/vext/ref/fb/transformpropertytrackdata). |

### TransformPropertyTrackData {#constructor-4}

> **TransformPropertyTrackData**(other: [DataContainer](/vext/ref/shared/type/datacontainer))

Casts an instance of type [DataContainer](/vext/ref/shared/type/datacontainer) to [TransformPropertyTrackData](/vext/ref/fb/transformpropertytrackdata). Will throw an error when trying to cast from an unsupported type.

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **other** | [DataContainer](/vext/ref/shared/type/datacontainer) | The instance to cast to [TransformPropertyTrackData](/vext/ref/fb/transformpropertytrackdata). |

## Properties

### {{% prop-heading "values" %}}

> **[LinearTransform](/vext/ref/shared/type/lineartransform)**[]

## Static members

### {{% static-heading "typeInfo" %}}

> **[TypeInformation](/vext/ref/shared/type/typeinformation)**

The type information for the [TransformPropertyTrackData](/vext/ref/fb/transformpropertytrackdata) type.

