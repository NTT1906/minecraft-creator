---
author: mammerla
ms.author: mikeam
title: Entity Documentation - enum_property
ms.prod: gaming
---

# Entity Documentation - enum_property

Returns true when the `enum` actor property matches the value provided.

## Parameters

|Name |Default Value  |Type  |Description  |
|---------|---------|---------|---------|
| domain| *not set* |String | (Required) The property name to look for. |
| operator|equals |String | (Optional) The comparison to apply with 'value'.|
| value|*not set* |String | (Required) A string value. |

### operator

| Options| Description |
|:-----------|:-----------|
| !=| Test for inequality. |
| <| Test for less-than the value. |
| <=| Test for less-than or equal to the value. |
| <>| Test for inequality. |
| =| Test for equality. |
| ==| Test for equality. |
| >| Test for greater-than the value. |
| >=| Test for greater-than or equal to the value. |
| equals| Test for equality. |
| not| Test for inequality. |

### subject

| Options| Description |
|:-----------|:-----------|
| block| The block involved with the interaction. |
| damager| The damaging actor involved with the interaction. |
| other| The other member of an interaction, not the caller. |
| parent| The caller's current parent. |
| player| The player involved with the interaction. |
| self| The entity or object calling the test |
| target| The caller's current target. |


## Examples

### Full

```json
{ "test": "enum_property", "subject": "self", "domain": "minecraft:can_climb", "operator": "equals", "value": "" }
```

### Short (using Defaults)

```json
{ "test": "enum_property", "domain": "minecraft:can_climb", "value": "" }
```

## Vanilla entity examples

No entities currently use `enum_property`

## Vanilla entities using `enum_property`

No entities currently use `enum_property`
