---
# DO NOT TOUCH — This file was automatically generated. See https://github.com/mojang/minecraftapidocsgenerator to modify descriptions, examples, etc.
author: jakeshirley
ms.author: jashir
ms.prod: gaming
title: minecraft/server.IExplosionAfterEventSignal Class
description: Contents of the @minecraft/server.IExplosionAfterEventSignal class.
---
# IExplosionAfterEventSignal Class

> [!CAUTION]
> This class is still in pre-release.  Its signature may change or it may be removed in future releases.

## Classes that extend IExplosionAfterEventSignal
- [*ExplosionAfterEventSignal*](ExplosionAfterEventSignal.md)

Provides an adaptable interface for callers to subscribe to an event that fires after an explosion occurs.

## Methods
- [subscribe](#subscribe)
- [unsubscribe](#unsubscribe)

### **subscribe**
`
subscribe(callback: (arg: ExplosionAfterEvent) => void): (arg: ExplosionAfterEvent) => void
`

#### **Parameters**
- **callback**: (arg: [*ExplosionAfterEvent*](ExplosionAfterEvent.md)) => *void*

#### **Returns** (arg: [*ExplosionAfterEvent*](ExplosionAfterEvent.md)) => *void*

> [!IMPORTANT]
> This function can't be called in read-only mode.

### **unsubscribe**
`
unsubscribe(callback: (arg: ExplosionAfterEvent) => void): void
`

#### **Parameters**
- **callback**: (arg: [*ExplosionAfterEvent*](ExplosionAfterEvent.md)) => *void*

> [!IMPORTANT]
> This function can't be called in read-only mode.

> [!WARNING]
> This function can throw errors.
