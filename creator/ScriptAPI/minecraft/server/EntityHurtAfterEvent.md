---
# DO NOT TOUCH — This file was automatically generated. See https://github.com/mojang/minecraftapidocsgenerator to modify descriptions, examples, etc.
author: jakeshirley
ms.author: jashir
ms.prod: gaming
title: minecraft/server.EntityHurtAfterEvent Class
description: Contents of the @minecraft/server.EntityHurtAfterEvent class.
---
# EntityHurtAfterEvent Class

> [!CAUTION]
> This class is still in pre-release.  Its signature may change or it may be removed in future releases.

Contains information related to an entity getting hurt.

## Properties

### **damage**
`read-only damage: number;`

Describes the amount of damage caused.

Type: *number*

### **damageSource**
`read-only damageSource: EntityDamageSource;`

Source information on the entity that may have applied this damage.

Type: [*EntityDamageSource*](EntityDamageSource.md)

### **hurtEntity**
`read-only hurtEntity: Entity;`

Entity that was hurt.

Type: [*Entity*](Entity.md)
