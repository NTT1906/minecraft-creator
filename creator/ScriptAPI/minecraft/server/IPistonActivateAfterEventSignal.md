---
# DO NOT TOUCH — This file was automatically generated. See https://github.com/mojang/minecraftapidocsgenerator to modify descriptions, examples, etc.
author: jakeshirley
ms.author: jashir
ms.prod: gaming
title: minecraft/server.IPistonActivateAfterEventSignal Class
description: Contents of the @minecraft/server.IPistonActivateAfterEventSignal class.
---
# IPistonActivateAfterEventSignal Class

> [!CAUTION]
> This class is still in pre-release.  Its signature may change or it may be removed in future releases.

## Classes that extend IPistonActivateAfterEventSignal
- [*PistonActivateAfterEventSignal*](PistonActivateAfterEventSignal.md)

Provides an adaptable interface for callers to subscribe to an event that fires after a piston is activated.

## Methods
- [subscribe](#subscribe)
- [unsubscribe](#unsubscribe)

### **subscribe**
`
subscribe(callback: (arg: PistonActivateAfterEvent) => void): (arg: PistonActivateAfterEvent) => void
`

#### **Parameters**
- **callback**: (arg: [*PistonActivateAfterEvent*](PistonActivateAfterEvent.md)) => *void*

#### **Returns** (arg: [*PistonActivateAfterEvent*](PistonActivateAfterEvent.md)) => *void*

> [!IMPORTANT]
> This function can't be called in read-only mode.

### **unsubscribe**
`
unsubscribe(callback: (arg: PistonActivateAfterEvent) => void): void
`

#### **Parameters**
- **callback**: (arg: [*PistonActivateAfterEvent*](PistonActivateAfterEvent.md)) => *void*

> [!IMPORTANT]
> This function can't be called in read-only mode.

> [!WARNING]
> This function can throw errors.
