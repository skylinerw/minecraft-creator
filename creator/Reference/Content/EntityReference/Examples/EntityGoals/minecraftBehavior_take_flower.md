---
author: v-josjones
ms.author: v-josjones
title: minecraft:behavior.take_flower
ms.prod: gaming
---

# minecraft:behavior.take_flower

`minecraft:behavior.take_flower` allows an entity to receive flowers when presented from the `iron_golem` entity.

> [!NOTE]
> This behavior can only be used by the `villager` entity type.

## Example

```json
"minecraft:behavior.take_flower":{
    "priority": 2,
}
```

## Vanilla entities examples

### villager_v2

:::code language="json" source="../../../../Source/VanillaBehaviorPack/entities/villager_v2.json" range="1148-1150":::

## Vanilla entities using `minecraft:behavior.take_flower`

- [villager_v2](../../../../Source/VanillaBehaviorPack_Snippets/entities/villager_v2.md)
- [villager](../../../../Source/VanillaBehaviorPack_Snippets/entities/villager.md)
