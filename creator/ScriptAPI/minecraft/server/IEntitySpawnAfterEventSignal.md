---
# DO NOT TOUCH — This file was automatically generated. See https://github.com/mojang/minecraftapidocsgenerator to modify descriptions, examples, etc.
author: jakeshirley
ms.author: jashir
ms.prod: gaming
title: minecraft/server.IEntitySpawnAfterEventSignal Class
description: Contents of the @minecraft/server.IEntitySpawnAfterEventSignal class.
---
# IEntitySpawnAfterEventSignal Class

> [!CAUTION]
> This class is still in pre-release.  Its signature may change or it may be removed in future releases.

## Classes that extend IEntitySpawnAfterEventSignal
- [*EntitySpawnAfterEventSignal*](EntitySpawnAfterEventSignal.md)

Provides an adaptable interface for callers to subscribe to an event that fires after an entity is spawned.

## Methods
- [subscribe](#subscribe)
- [unsubscribe](#unsubscribe)

### **subscribe**
`
subscribe(callback: (arg: EntitySpawnAfterEvent) => void): (arg: EntitySpawnAfterEvent) => void
`

#### **Parameters**
- **callback**: (arg: [*EntitySpawnAfterEvent*](EntitySpawnAfterEvent.md)) => *void*

#### **Returns** (arg: [*EntitySpawnAfterEvent*](EntitySpawnAfterEvent.md)) => *void*

> [!IMPORTANT]
> This function can't be called in read-only mode.

### **unsubscribe**
`
unsubscribe(callback: (arg: EntitySpawnAfterEvent) => void): void
`

#### **Parameters**
- **callback**: (arg: [*EntitySpawnAfterEvent*](EntitySpawnAfterEvent.md)) => *void*

> [!IMPORTANT]
> This function can't be called in read-only mode.

> [!WARNING]
> This function can throw errors.
