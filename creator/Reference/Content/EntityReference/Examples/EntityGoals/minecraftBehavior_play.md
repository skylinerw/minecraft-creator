---
author: v-josjones
ms.author: v-josjones
title: minecraft:behavior.play
ms.prod: gaming
---

# minecraft:behavior.play

`minecraft:behavior.play` allows an entity to play with entities that have been tagged as `baby`.

> [!NOTE]
> This behavior can only be used by the `villager` entity type.

## Parameters

|Name |Default Value  |Type  |Description  |
|:----------|:----------|:----------|:----------|
|speed_multiplier| 1.0| Decimal| Movement speed multiplier of the mob when using this AI Goal |

## Example

```json
"minecraft:behavior.play":{
    "priority": 2,
    "speed_multiplier": 1.0,
}
```

## Vanilla entities examples

### villager_v2

:::code language="json" source="../../../../Source/VanillaBehaviorPack/entities/villager_v2.json" range="523-526":::

## Vanilla entities using `minecraft:behavior.play`

- [villager_v2](../../../../Source/VanillaBehaviorPack_Snippets/entities/villager_v2.md)
- [villager](../../../../Source/VanillaBehaviorPack_Snippets/entities/villager.md)
