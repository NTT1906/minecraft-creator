---
# DO NOT TOUCH — This file was automatically generated. See https://github.com/mojang/minecraftapidocsgenerator to modify descriptions, examples, etc.
author: jakeshirley
ms.author: jashir
ms.prod: gaming
title: minecraft/server.IItemStartUseAfterEventSignal Class
description: Contents of the @minecraft/server.IItemStartUseAfterEventSignal class.
---
# IItemStartUseAfterEventSignal Class

> [!CAUTION]
> This class is still in pre-release.  Its signature may change or it may be removed in future releases.

## Classes that extend IItemStartUseAfterEventSignal
- [*ItemStartUseAfterEventSignal*](ItemStartUseAfterEventSignal.md)

## Methods
- [subscribe](#subscribe)
- [unsubscribe](#unsubscribe)

### **subscribe**
`
subscribe(callback: (arg: ItemStartUseAfterEvent) => void): (arg: ItemStartUseAfterEvent) => void
`

#### **Parameters**
- **callback**: (arg: [*ItemStartUseAfterEvent*](ItemStartUseAfterEvent.md)) => *void*

#### **Returns** (arg: [*ItemStartUseAfterEvent*](ItemStartUseAfterEvent.md)) => *void*

> [!IMPORTANT]
> This function can't be called in read-only mode.

### **unsubscribe**
`
unsubscribe(callback: (arg: ItemStartUseAfterEvent) => void): void
`

#### **Parameters**
- **callback**: (arg: [*ItemStartUseAfterEvent*](ItemStartUseAfterEvent.md)) => *void*

> [!IMPORTANT]
> This function can't be called in read-only mode.

> [!WARNING]
> This function can throw errors.
