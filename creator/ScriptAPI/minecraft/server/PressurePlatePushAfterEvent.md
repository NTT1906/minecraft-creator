---
# DO NOT TOUCH — This file was automatically generated. See https://github.com/mojang/minecraftapidocsgenerator to modify descriptions, examples, etc.
author: jakeshirley
ms.author: jashir
ms.prod: gaming
title: minecraft/server.PressurePlatePushAfterEvent Class
description: Contents of the @minecraft/server.PressurePlatePushAfterEvent class.
---
# PressurePlatePushAfterEvent Class

> [!CAUTION]
> This class is still in pre-release.  Its signature may change or it may be removed in future releases.

## Extends
- [*BlockEvent*](BlockEvent.md)

Contains information related to changes to a pressure plate push.

## Properties

### **previousRedstonePower**
`read-only previousRedstonePower: number;`

The redstone power of the pressure plate before it was pushed.

Type: *number*

### **redstonePower**
`read-only redstonePower: number;`

The redstone power of the pressure plate at the time of the push.

Type: *number*

### **source**
`read-only source: Entity;`

Source that triggered the pressure plate push.

Type: [*Entity*](Entity.md)
