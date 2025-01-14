---
author: v-josjones
ms.author: v-josjones
title: minecraft:behavior.move_to_land
ms.prod: gaming
---

# minecraft:behavior.move_to_land

`minecraft:behavior.move_to_land` allows an entity to move to land when in a non-land medium such as lava or water.

## Parameters

|Name |Default Value  |Type  |Description  |
|:----------|:----------|:----------|:----------|
|goal_radius| 0.5| Decimal| Distance in blocks within the mob considers it has reached the goal. This is the "wiggle room" to stop the AI from bouncing back and forth trying to reach a specific spot |
|search_count| 10| Integer| The number of blocks each tick that the mob will check within it's search range and height for a valid block to move to. A value of 0 will have the mob check every block within range in one tick |
|search_height| 1| Integer| Height in blocks the mob will look for land to move towards |
|search_range| 0| Integer| The distance in blocks it will look for land to move towards |
|speed_multiplier| 1.0| Decimal| Movement speed multiplier of the mob when using this AI Goal |

## Example

```json
"minecraft:behavior.move_to_land":{
    "priority": 2,
    "search_range": 25,
    "search_height": 5,
    "goal_radius": 0.75,
    "search_count": 10
}
```

## Vanilla entities examples

### turtle

:::code language="json" source="../../../../Source/VanillaBehaviorPack/entities/turtle.json" range="86-91":::

## Vanilla entities using `minecraft:behavior.move_to_land`

- [turtle](../../../../Source/VanillaBehaviorPack_Snippets/entities/turtle.md)
