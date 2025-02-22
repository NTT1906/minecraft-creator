---
# DO NOT TOUCH — This file was automatically generated. See https://github.com/mojang/minecraftapidocsgenerator to modify descriptions, examples, etc.
author: jakeshirley
ms.author: jashir
ms.prod: gaming
title: minecraft/server.IItemUseOnAfterEventSignal Class
description: Contents of the @minecraft/server.IItemUseOnAfterEventSignal class.
---
# IItemUseOnAfterEventSignal Class

> [!CAUTION]
> This class is still in pre-release.  Its signature may change or it may be removed in future releases.

## Classes that extend IItemUseOnAfterEventSignal
- [*ItemUseOnAfterEventSignal*](ItemUseOnAfterEventSignal.md)

Provides an adaptable interface for callers to subscribe to an event that fires after an item is used on a block.

## Methods
- [subscribe](#subscribe)
- [unsubscribe](#unsubscribe)

### **subscribe**
`
subscribe(callback: (arg: ItemUseOnAfterEvent) => void): (arg: ItemUseOnAfterEvent) => void
`

#### **Parameters**
- **callback**: (arg: [*ItemUseOnAfterEvent*](ItemUseOnAfterEvent.md)) => *void*

#### **Returns** (arg: [*ItemUseOnAfterEvent*](ItemUseOnAfterEvent.md)) => *void*

> [!IMPORTANT]
> This function can't be called in read-only mode.

### **unsubscribe**
`
unsubscribe(callback: (arg: ItemUseOnAfterEvent) => void): void
`

#### **Parameters**
- **callback**: (arg: [*ItemUseOnAfterEvent*](ItemUseOnAfterEvent.md)) => *void*

> [!IMPORTANT]
> This function can't be called in read-only mode.

> [!WARNING]
> This function can throw errors.
