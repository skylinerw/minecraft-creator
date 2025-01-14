---
author: v-josjones
ms.author: v-josjones
title: minecraft:behavior.rise_to_liquid_level
ms.prod: gaming
---

# minecraft:behavior.rise_to_liquid_level

`minecraft:behavior.rise_to_liquid_level` allows an entity to rise to the top of a liquid block if they are located in one or have spawned under a liquid block.

## Parameter

|Name |Default Value  |Type  |Description  |
|:----------|:----------|:----------|:----------|
|liquid_y_offset| 0.0| Decimal| Vertical offset from the liquid |
|rise_delta | 0.0| Decimal| displacement for how much the entity will move up in the vertical axis|
|sink_delta | 0.0| Decimal| displacement for how much the entity will move down in the vertical axis|

## Example

```json
"minecraft:behavior.rise_to_liquid_level":{
    "priority": 0,
    "liquid_y_offset": 0.25,
    "rise_delta": 0.5,
    "sink_delta": 0.5
}
```

## Vanilla entities examples

### strider

:::code language="json" source="../../../../Source/VanillaBehaviorPack/entities/strider.json" range="270-275":::

## Vanilla entities using `minecraft:behavior.rise_to_liquid_level`

- [strider](../../../../Source/VanillaBehaviorPack_Snippets/entities/strider.md)
