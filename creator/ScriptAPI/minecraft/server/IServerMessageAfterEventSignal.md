---
# DO NOT TOUCH — This file was automatically generated. See https://github.com/mojang/minecraftapidocsgenerator to modify descriptions, examples, etc.
author: jakeshirley
ms.author: jashir
ms.prod: gaming
title: minecraft/server.IServerMessageAfterEventSignal Class
description: Contents of the @minecraft/server.IServerMessageAfterEventSignal class.
---
# IServerMessageAfterEventSignal Class

> [!CAUTION]
> This class is still in pre-release.  Its signature may change or it may be removed in future releases.

## Classes that extend IServerMessageAfterEventSignal
- [*ServerMessageAfterEventSignal*](ServerMessageAfterEventSignal.md)

Provides an adaptable interface for callers to subscribe to an event that fires after a server message is sent. Note that this event is for internal use only.

## Methods
- [subscribe](#subscribe)
- [unsubscribe](#unsubscribe)

### **subscribe**
`
subscribe(callback: (arg: MessageReceiveAfterEvent) => void): (arg: MessageReceiveAfterEvent) => void
`

#### **Parameters**
- **callback**: (arg: [*MessageReceiveAfterEvent*](MessageReceiveAfterEvent.md)) => *void*

#### **Returns** (arg: [*MessageReceiveAfterEvent*](MessageReceiveAfterEvent.md)) => *void*

> [!IMPORTANT]
> This function can't be called in read-only mode.

### **unsubscribe**
`
unsubscribe(callback: (arg: MessageReceiveAfterEvent) => void): void
`

#### **Parameters**
- **callback**: (arg: [*MessageReceiveAfterEvent*](MessageReceiveAfterEvent.md)) => *void*

> [!IMPORTANT]
> This function can't be called in read-only mode.

> [!WARNING]
> This function can throw errors.
