---
# DO NOT TOUCH — This file was automatically generated. See https://github.com/mojang/minecraftapidocsgenerator to modify descriptions, examples, etc.
author: jakeshirley
ms.author: jashir
ms.prod: gaming
title: minecraft/server.IItemCompleteUseAfterEventSignal Class
description: Contents of the @minecraft/server.IItemCompleteUseAfterEventSignal class.
---
# IItemCompleteUseAfterEventSignal Class

> [!CAUTION]
> This class is still in pre-release.  Its signature may change or it may be removed in future releases.

## Classes that extend IItemCompleteUseAfterEventSignal
- [*ItemCompleteUseAfterEventSignal*](ItemCompleteUseAfterEventSignal.md)

## Methods
- [subscribe](#subscribe)
- [unsubscribe](#unsubscribe)

### **subscribe**
`
subscribe(callback: (arg: ItemCompleteUseAfterEvent) => void): (arg: ItemCompleteUseAfterEvent) => void
`

#### **Parameters**
- **callback**: (arg: [*ItemCompleteUseAfterEvent*](ItemCompleteUseAfterEvent.md)) => *void*

#### **Returns** (arg: [*ItemCompleteUseAfterEvent*](ItemCompleteUseAfterEvent.md)) => *void*

> [!IMPORTANT]
> This function can't be called in read-only mode.

### **unsubscribe**
`
unsubscribe(callback: (arg: ItemCompleteUseAfterEvent) => void): void
`

#### **Parameters**
- **callback**: (arg: [*ItemCompleteUseAfterEvent*](ItemCompleteUseAfterEvent.md)) => *void*

> [!IMPORTANT]
> This function can't be called in read-only mode.

> [!WARNING]
> This function can throw errors.
