---
# DO NOT TOUCH — This file was automatically generated. See https://github.com/mojang/minecraftapidocsgenerator to modify descriptions, examples, etc.
author: jakeshirley
ms.author: jashir
ms.prod: gaming
title: minecraft/server.IPressurePlatePopAfterEventSignal Class
description: Contents of the @minecraft/server.IPressurePlatePopAfterEventSignal class.
---
# IPressurePlatePopAfterEventSignal Class

> [!CAUTION]
> This class is still in pre-release.  Its signature may change or it may be removed in future releases.

## Classes that extend IPressurePlatePopAfterEventSignal
- [*PressurePlatePopAfterEventSignal*](PressurePlatePopAfterEventSignal.md)

## Methods
- [subscribe](#subscribe)
- [unsubscribe](#unsubscribe)

### **subscribe**
`
subscribe(callback: (arg: PressurePlatePopAfterEvent) => void): (arg: PressurePlatePopAfterEvent) => void
`

#### **Parameters**
- **callback**: (arg: [*PressurePlatePopAfterEvent*](PressurePlatePopAfterEvent.md)) => *void*

#### **Returns** (arg: [*PressurePlatePopAfterEvent*](PressurePlatePopAfterEvent.md)) => *void*

> [!IMPORTANT]
> This function can't be called in read-only mode.

### **unsubscribe**
`
unsubscribe(callback: (arg: PressurePlatePopAfterEvent) => void): void
`

#### **Parameters**
- **callback**: (arg: [*PressurePlatePopAfterEvent*](PressurePlatePopAfterEvent.md)) => *void*

> [!IMPORTANT]
> This function can't be called in read-only mode.

> [!WARNING]
> This function can throw errors.
