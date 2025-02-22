---
author: mammerla
ms.author: v-jillheaden
title: Entity Documentation - minecraft:player.level
ms.prod: gaming
---

# Entity Documentation - minecraft:player.level

`minecraft:player.level` defines the player's level.

## Parameters

| Name| Default Value| Type| Description |
|:-----------:|:-----------:|:-----------:|:-----------:|
|max| *not set*| Integer| The maximum player level value of the entity. |
|value| *not set*| Integer|  The initial value of the player level. |

## Example

```json
"minecraft:player.level": {
        "value": 0,
        "max": 24791
      }
```

## Vanilla entities examples

### player

```json
"minecraft:player.level": {
        "value": 0,
        "max": 24791
      }
```

## Vanilla entities using `minecraft:exhaustion_values`

- [player](../../../../Source/VanillaBehaviorPack_Snippets/entities/player.md)