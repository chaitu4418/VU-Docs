---
title: FogEffectState
---

Inherits from [DataContainer](/vext/ref/shared/type/datacontainer)

## Summary

### Constructors

|  |
| --- |
| **[FogEffectState](#constructor-0)**() |
| **[FogEffectState](#constructor-1)**(guid: [Guid](/vext/ref/shared/type/guid)) |
| **[FogEffectState](#constructor-2)**(other: [DataContainer](/vext/ref/shared/type/datacontainer)) |

### Properties

| Name | Type |
| ---- | ---- |
| {{< prop "fogColorCurve" >}} | [Vec4](/vext/ref/shared/type/vec4) |
| {{< prop "curve" >}} | [Vec4](/vext/ref/shared/type/vec4) |
| {{< prop "fogColor" >}} | [Vec3](/vext/ref/shared/type/vec3) |
| {{< prop "start" >}} | float |
| {{< prop "endValue" >}} | float |
| {{< prop "fogColorStart" >}} | float |
| {{< prop "fogColorEnd" >}} | float |
| {{< prop "heightFogVisibilityRange" >}} | float |
| {{< prop "transparencyFadeStart" >}} | float |
| {{< prop "transparencyFadeEnd" >}} | float |
| {{< prop "transparencyFadeClamp" >}} | float |
| {{< prop "heightFogDepth" >}} | float |
| {{< prop "heightFogFollowCamera" >}} | float |
| {{< prop "heightFogAltitude" >}} | float |
| {{< prop "heightFogEnable" >}} | bool |
| {{< prop "enable" >}} | bool |

### Static members

| Name | Type |
| ---- | ---- |
| {{< static "FogEffectState" "typeInfo" >}} | [TypeInformation](/vext/ref/shared/type/typeinformation) |

## Constructors

### FogEffectState {#constructor-0}

> **FogEffectState**()

Creates a new [FogEffectState](/vext/ref/fb/fogeffectstate) frostbite instance.

### FogEffectState {#constructor-1}

> **FogEffectState**(guid: [Guid](/vext/ref/shared/type/guid))

Creates a new [FogEffectState](/vext/ref/fb/fogeffectstate) frostbite instance and assigns it the provided [Guid](/vext/ref/shared/type/guid).

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **guid** | [Guid](/vext/ref/shared/type/guid) | The [Guid](/vext/ref/shared/type/guid) to assign to the newly created instance. |

### FogEffectState {#constructor-2}

> **FogEffectState**(other: [DataContainer](/vext/ref/shared/type/datacontainer))

Casts an instance of type [DataContainer](/vext/ref/shared/type/datacontainer) to [FogEffectState](/vext/ref/fb/fogeffectstate). Will throw an error when trying to cast from an unsupported type.

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **other** | [DataContainer](/vext/ref/shared/type/datacontainer) | The instance to cast to [FogEffectState](/vext/ref/fb/fogeffectstate). |

## Properties

### {{% prop-heading "fogColorCurve" %}}

> **[Vec4](/vext/ref/shared/type/vec4)**

### {{% prop-heading "curve" %}}

> **[Vec4](/vext/ref/shared/type/vec4)**

### {{% prop-heading "fogColor" %}}

> **[Vec3](/vext/ref/shared/type/vec3)**

### {{% prop-heading "start" %}}

> **float**

### {{% prop-heading "endValue" %}}

> **float**

### {{% prop-heading "fogColorStart" %}}

> **float**

### {{% prop-heading "fogColorEnd" %}}

> **float**

### {{% prop-heading "heightFogVisibilityRange" %}}

> **float**

### {{% prop-heading "transparencyFadeStart" %}}

> **float**

### {{% prop-heading "transparencyFadeEnd" %}}

> **float**

### {{% prop-heading "transparencyFadeClamp" %}}

> **float**

### {{% prop-heading "heightFogDepth" %}}

> **float**

### {{% prop-heading "heightFogFollowCamera" %}}

> **float**

### {{% prop-heading "heightFogAltitude" %}}

> **float**

### {{% prop-heading "heightFogEnable" %}}

> **bool**

### {{% prop-heading "enable" %}}

> **bool**

## Static members

### {{% static-heading "typeInfo" %}}

> **[TypeInformation](/vext/ref/shared/type/typeinformation)**

The type information for the [FogEffectState](/vext/ref/fb/fogeffectstate) type.

