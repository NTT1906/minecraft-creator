---
# DO NOT TOUCH — This file was automatically generated. See https://github.com/mojang/minecraftapidocsgenerator to modify descriptions, examples, etc.
author: jakeshirley
ms.author: jashir
ms.prod: gaming
title: minecraft/server.IItemStopUseAfterEventSignal Class
description: Contents of the @minecraft/server.IItemStopUseAfterEventSignal class.
---
# IItemStopUseAfterEventSignal Class

> [!CAUTION]
> This class is still in pre-release.  Its signature may change or it may be removed in future releases.

## Classes that extend IItemStopUseAfterEventSignal
- [*ItemStopUseAfterEventSignal*](ItemStopUseAfterEventSignal.md)

## Methods
- [subscribe](#subscribe)
- [unsubscribe](#unsubscribe)

### **subscribe**
`
subscribe(callback: (arg: ItemStopUseAfterEvent) => void): (arg: ItemStopUseAfterEvent) => void
`

#### **Parameters**
- **callback**: (arg: [*ItemStopUseAfterEvent*](ItemStopUseAfterEvent.md)) => *void*

#### **Returns** (arg: [*ItemStopUseAfterEvent*](ItemStopUseAfterEvent.md)) => *void*

> [!IMPORTANT]
> This function can't be called in read-only mode.

### **unsubscribe**
`
unsubscribe(callback: (arg: ItemStopUseAfterEvent) => void): void
`

#### **Parameters**
- **callback**: (arg: [*ItemStopUseAfterEvent*](ItemStopUseAfterEvent.md)) => *void*

> [!IMPORTANT]
> This function can't be called in read-only mode.

> [!WARNING]
> This function can throw errors.
