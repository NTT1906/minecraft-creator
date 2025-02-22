---
# DO NOT TOUCH — This file was automatically generated. See https://github.com/mojang/minecraftapidocsgenerator to modify descriptions, examples, etc.
author: jakeshirley
ms.author: jashir
ms.prod: gaming
title: minecraft/server-gametest Module
description: Contents of the @minecraft/server-gametest module
---
# @minecraft/server-gametest Module

The @minecraft/server-gametest module provides scriptable APIs for scaffolding and testing content experiences in Minecraft.

> [!CAUTION]
> This module is still in pre-release.  It may change or it may be removed in future releases.

## Manifest Details
```json
{
    "module_name": "@minecraft/server-gametest",
    "version": "1.0.0-beta"
}
```

## Available Versions
- `1.0.0-beta`

## Enumerations
- [GameTestErrorType](GameTestErrorType.md)

## Classes
- [FenceConnectivity](FenceConnectivity.md)
- [GameTestSequence](GameTestSequence.md)
- [RegistrationBuilder](RegistrationBuilder.md)
- [SculkSpreader](SculkSpreader.md)
- [SimulatedPlayer](SimulatedPlayer.md)
- [Tags](Tags.md)
- [Test](Test.md)

## Interfaces
- [GameTestErrorContext](GameTestErrorContext.md)

## Errors
- [GameTestError](GameTestError.md)

## Functions

### **register**
`
register(testClassName: string, testName: string, testFunction: (arg: Test) => void): RegistrationBuilder
`

Registers a new GameTest function. This GameTest will become available in Minecraft via /gametest run [testClassName]:[testName].

#### **Parameters**
- **testClassName**: *string*
  
  Name of the class of tests this test should be a part of.
- **testName**: *string*
  
  Name of this specific test.
- **testFunction**: (arg: [*Test*](Test.md)) => *void*
  
  Implementation of the test function.

#### **Returns** [*RegistrationBuilder*](RegistrationBuilder.md) - Returns a [*@minecraft/server-gametest.RegistrationBuilder*](../../minecraft/server-gametest/RegistrationBuilder.md) object where additional options for this test can be specified via builder methods.

> [!IMPORTANT]
> This function can't be called in read-only mode.

#### Examples
##### ***example1.js***
```typescript
GameTest.register("ExampleTests", "alwaysFail", (test) => {
  test.fail("This test, runnable via '/gametest run ExampleTests:alwaysFail', will always fail");
});
```
##### ***simpleMobTest.ts***
```typescript
gt.register("StarterTests", "simpleMobTest", (test: gt.Test) => {
  const attackerId = "fox";
  const victimId = "chicken";

  test.spawn(attackerId, { x: 5, y: 2, z: 5 });
  test.spawn(victimId, { x: 2, y: 2, z: 2 });

  test.assertEntityPresentInArea(victimId, true);

  test.succeedWhen(() => {
    test.assertEntityPresentInArea(victimId, false);
  });
})
  .maxTicks(400)
  .structureName("gametests:mediumglass");
```

### **registerAsync**
`
registerAsync(testClassName: string, testName: string, testFunction: (arg: Test) => Promise<void>): RegistrationBuilder
`

Registers a new GameTest function that is designed for asynchronous execution. This GameTest will become available in Minecraft via /gametest run [testClassName]:[testName].

#### **Parameters**
- **testClassName**: *string*
  
  Name of the class of tests this test should be a part of.
- **testName**: *string*
  
  Name of this specific test.
- **testFunction**: (arg: [*Test*](Test.md)) => Promise&lt;*void*&gt;
  
  Implementation of the test function.

#### **Returns** [*RegistrationBuilder*](RegistrationBuilder.md) - Returns a [*@minecraft/server-gametest.RegistrationBuilder*](../../minecraft/server-gametest/RegistrationBuilder.md) object where additional options for this test can be specified via builder methods.

> [!IMPORTANT]
> This function can't be called in read-only mode.

## Change Log
## 1.0.0-beta
#### Added `@minecraft/server-gametest` Module
