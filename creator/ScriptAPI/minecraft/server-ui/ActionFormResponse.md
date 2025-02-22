---
# DO NOT TOUCH — This file was automatically generated. See https://github.com/mojang/minecraftapidocsgenerator to modify descriptions, examples, etc.
author: jakeshirley
ms.author: jashir
ms.prod: gaming
title: minecraft/server-ui.ActionFormResponse Class
description: Contents of the @minecraft/server-ui.ActionFormResponse class.
---
# ActionFormResponse Class

## Extends
- [*FormResponse*](FormResponse.md)

Returns data about the player results from a modal action form.

## Properties

### **selection**
`read-only selection?: number;`

Returns the index of the button that was pushed.

Type: *number*

#### Examples
##### ***showActionForm.ts***
```typescript
  const playerList = mc.world.getPlayers();

  if (playerList.length >= 1) {
    const form = new mcui.ActionFormData()
      .title("Test Title")
      .body("Body text here!")
      .button("btn 1")
      .button("btn 2")
      .button("btn 3")
      .button("btn 4")
      .button("btn 5");

    const result = await form.show(playerList[0]);

    if (result.canceled) {
      log("Player exited out of the dialog. Note that if the chat window is up, dialogs are automatically canceled.");
      return -1;
    } else {
      log("Your result was: " + result.selection);
    }
  }
```
##### ***showFavoriteMonth.ts***
```typescript
  const players = mc.world.getPlayers();

  if (players.length >= 1) {
    const form = new mcui.ActionFormData()
      .title("Months")
      .body("Choose your favorite month!")
      .button("January")
      .button("February")
      .button("March")
      .button("April")
      .button("May");

    form.show(players[0]).then((response: mcui.ActionFormResponse) => {
      if (response.selection === 3) {
        log("I like April too!");
        return -1;
      }
    });
  }
```
