---
# DO NOT TOUCH — This file was automatically generated. See https://github.com/mojang/minecraftapidocsgenerator to modify descriptions, examples, etc.
author: jakeshirley
ms.author: jashir
ms.prod: gaming
title: minecraft/server-editor.IEventToken Interface
description: Contents of the @minecraft/server-editor.IEventToken class.
---
# IEventToken Interface

Returned from an event subscription. Provides functionality for cleaning up listeners

## Methods
- [unsubscribe](#unsubscribe)

### **unsubscribe**
`
unsubscribe(): void
`

Removes registered listener from an event

#### **Returns** *void*

> [!IMPORTANT]
> This function can't be called in read-only mode.
