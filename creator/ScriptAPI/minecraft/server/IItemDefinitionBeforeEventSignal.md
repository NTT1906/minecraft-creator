---
# DO NOT TOUCH — This file was automatically generated. See https://github.com/mojang/minecraftapidocsgenerator to modify descriptions, examples, etc.
author: jakeshirley
ms.author: jashir
ms.prod: gaming
title: minecraft/server.IItemDefinitionBeforeEventSignal Class
description: Contents of the @minecraft/server.IItemDefinitionBeforeEventSignal class.
---
# IItemDefinitionBeforeEventSignal Class

> [!CAUTION]
> This class is still in pre-release.  Its signature may change or it may be removed in future releases.

## Classes that extend IItemDefinitionBeforeEventSignal
- [*ItemDefinitionBeforeEventSignal*](ItemDefinitionBeforeEventSignal.md)

Provides an adaptable interface for callers to subscribe to an event that fires before an items' definition changes.

## Methods
- [subscribe](#subscribe)
- [unsubscribe](#unsubscribe)

### **subscribe**
`
subscribe(callback: (arg: ItemDefinitionTriggeredBeforeEvent) => void): (arg: ItemDefinitionTriggeredBeforeEvent) => void
`

#### **Parameters**
- **callback**: (arg: [*ItemDefinitionTriggeredBeforeEvent*](ItemDefinitionTriggeredBeforeEvent.md)) => *void*

#### **Returns** (arg: [*ItemDefinitionTriggeredBeforeEvent*](ItemDefinitionTriggeredBeforeEvent.md)) => *void*

> [!IMPORTANT]
> This function can't be called in read-only mode.

### **unsubscribe**
`
unsubscribe(callback: (arg: ItemDefinitionTriggeredBeforeEvent) => void): void
`

#### **Parameters**
- **callback**: (arg: [*ItemDefinitionTriggeredBeforeEvent*](ItemDefinitionTriggeredBeforeEvent.md)) => *void*

> [!IMPORTANT]
> This function can't be called in read-only mode.

> [!WARNING]
> This function can throw errors.
