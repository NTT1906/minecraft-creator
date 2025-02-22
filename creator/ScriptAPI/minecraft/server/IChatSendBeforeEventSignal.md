---
# DO NOT TOUCH — This file was automatically generated. See https://github.com/mojang/minecraftapidocsgenerator to modify descriptions, examples, etc.
author: jakeshirley
ms.author: jashir
ms.prod: gaming
title: minecraft/server.IChatSendBeforeEventSignal Class
description: Contents of the @minecraft/server.IChatSendBeforeEventSignal class.
---
# IChatSendBeforeEventSignal Class

> [!CAUTION]
> This class is still in pre-release.  Its signature may change or it may be removed in future releases.

## Classes that extend IChatSendBeforeEventSignal
- [*ChatSendBeforeEventSignal*](ChatSendBeforeEventSignal.md)

Provides an adaptable interface for callers to subscribe to an event that fires before a chat message is sent.

## Methods
- [subscribe](#subscribe)
- [unsubscribe](#unsubscribe)

### **subscribe**
`
subscribe(callback: (arg: ChatSendBeforeEvent) => void): (arg: ChatSendBeforeEvent) => void
`

#### **Parameters**
- **callback**: (arg: [*ChatSendBeforeEvent*](ChatSendBeforeEvent.md)) => *void*

#### **Returns** (arg: [*ChatSendBeforeEvent*](ChatSendBeforeEvent.md)) => *void*

> [!IMPORTANT]
> This function can't be called in read-only mode.

### **unsubscribe**
`
unsubscribe(callback: (arg: ChatSendBeforeEvent) => void): void
`

#### **Parameters**
- **callback**: (arg: [*ChatSendBeforeEvent*](ChatSendBeforeEvent.md)) => *void*

> [!IMPORTANT]
> This function can't be called in read-only mode.

> [!WARNING]
> This function can throw errors.
