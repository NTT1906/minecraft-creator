---
# DO NOT TOUCH — This file was automatically generated. See https://github.com/mojang/minecraftapidocsgenerator to modify descriptions, examples, etc.
author: jakeshirley
ms.author: jashir
ms.prod: gaming
title: minecraft/server.IItemDefinitionAfterEventSignal Class
description: Contents of the @minecraft/server.IItemDefinitionAfterEventSignal class.
---
# IItemDefinitionAfterEventSignal Class

> [!CAUTION]
> This class is still in pre-release.  Its signature may change or it may be removed in future releases.

## Classes that extend IItemDefinitionAfterEventSignal
- [*ItemDefinitionAfterEventSignal*](ItemDefinitionAfterEventSignal.md)

Provides an adaptable interface for callers to subscribe to an event that fires after an items' definition has changed.

## Methods
- [subscribe](#subscribe)
- [unsubscribe](#unsubscribe)

### **subscribe**
`
subscribe(callback: (arg: ItemDefinitionTriggeredAfterEvent) => void): (arg: ItemDefinitionTriggeredAfterEvent) => void
`

#### **Parameters**
- **callback**: (arg: [*ItemDefinitionTriggeredAfterEvent*](ItemDefinitionTriggeredAfterEvent.md)) => *void*

#### **Returns** (arg: [*ItemDefinitionTriggeredAfterEvent*](ItemDefinitionTriggeredAfterEvent.md)) => *void*

> [!IMPORTANT]
> This function can't be called in read-only mode.

### **unsubscribe**
`
unsubscribe(callback: (arg: ItemDefinitionTriggeredAfterEvent) => void): void
`

#### **Parameters**
- **callback**: (arg: [*ItemDefinitionTriggeredAfterEvent*](ItemDefinitionTriggeredAfterEvent.md)) => *void*

> [!IMPORTANT]
> This function can't be called in read-only mode.

> [!WARNING]
> This function can throw errors.
