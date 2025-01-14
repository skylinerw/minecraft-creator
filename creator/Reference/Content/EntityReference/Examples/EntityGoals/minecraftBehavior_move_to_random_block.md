---
author: v-josjones
ms.author: v-josjones
title: minecraft:behavior.move_to_random_block
ms.prod: gaming
---

# minecraft:behavior.move_to_random_block

`minecraft:behavior.move_to_random_block` allows an entity to move to a random block within a set radius.

## Parameters

|Name |Default Value  |Type  |Description  |
|:----------|:----------|:----------|:----------|
|block_distance| 16.0| Decimal| Defines the distance from the mob, in blocks, that the block to move to will be chosen. |
|within_radius| 0.0| Decimal|Defines the distance in blocks the mob has to be from the block for the movement to be finished. |

## Example

```json
"minecraft:behavior.move_to_random_block":{
    "priority": 2,
    "within_radius": 5.0,
    "block_distance": 128.0
}
```

## Vanilla entities examples

### pillager

:::code language="json" source="../../../../Source/VanillaBehaviorPack/entities/pillager.json" range="200-205":::

## Vanilla entities using `minecraft:behavior.move_to_random_block`

- [pillager](../../../../Source/VanillaBehaviorPack_Snippets/entities/pillager.md)
- [vindicator](../../../../Source/VanillaBehaviorPack_Snippets/entities/vindicator.md)
