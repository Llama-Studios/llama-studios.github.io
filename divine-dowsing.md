---
title: Divine Dowsing
nav_order: 6
---

# Divine Dowsing
![Screen Shot 2021-09-05 at 11 29 38 copy 2](https://user-images.githubusercontent.com/31634240/132233236-051552de-7118-470e-9a27-3fceae87dbf3.png)

Divine Dowsing is an addon that adds dowsing pseudoscience to Minecraft, making finding underground resources and structures easier.

[Download](/divinedowsing.mcaddon){: .btn } [Feedback and Bug Reports](https://docs.google.com/forms/d/e/1FAIpQLSeKr_PbqUBF1kBB8lWgr_bC1CY1TPUCAHrPu0u4AxsGWloGvQ/viewform){: .btn }

> By downloading this addon, you agree not to repost it and to follow the [license](/licensing.html)

> **Make sure you enable Holiday Creator Features and Beta APIs before playing!**

[Watch my video explaining how it works](https://www.youtube.com/watch?v=2LaVvnwws9o){: .btn }

## What is dowsing?
Dowsing is a psuedoscience (fake science) where people would carry around a stick (known as a dowsing rod), and if the stick moved in a certain way, it was believed that there was something important underground. This was traditionally used to find water for wells, but later to find caves, minerals, and oil deposits. Studies have shown that dowsing is no more accurate than random chance, but this addon brings actually useful dowsing to Minecraft.

## The Rods
There are 10 different types of dowsing rods that find different things:
- Oak - finds water
- Birch - finds ores
- Spruce - finds caves
- Jungle - finds underground structures
- Acacia - finds cave biomes
- Dark Oak - finds geodes
- Crimson - finds lava
- Warped - finds nether ores
- Cherry - finds decorative stone variants
- Mangrove - finds modded blocks

## Usage
To use a dowsing rod, hold it and interact (right-click). The results will appear in the chat:
![Screen Shot 2021-09-05 at 11 30 36 copy](https://user-images.githubusercontent.com/31634240/132234909-b0cf1283-d7a5-4160-bca8-b662afc9a065.png)

Since dowsing rods search in a + shape, digging straight down (while dangerous) will give you access to everything your rod found.

## Crafting
The basic rods are crafted from 4 logs and one enchanted stick:

|   |   | L |
|---|---|---|
|   | L | / |
| L |   | L |

L = log

/ = enchanted stick

Enchanted sticks are either dropped by witches, or made from enchantable sticks. Enchantable sticks are crafted like this:
|   | L |   |
|---|---|---|
| L | / | L |
|   | L |   |

L = lapis lazuli

/ = stick

Hold the enchantable stick and interact (right-click) to make an enchanted stick. This costs 4 levels.

### Upgrading
All of the dowsing rods can be upgraded to get more durability, more range, and a shorter cooldown. The following recipe is used to upgrade dowsing rods:

| A |   | A |
|---|---|---|
| G | I | / |
| A |   | A |

A = amethyst shard

G = gold block

I = iron block

/ = the dowsing rod you want to upgrade

## Compatibility
Divine Dowsing is now compatible with essentially any addon. The birch and warped dowsing rods now search for any block with an identifier ending in the word "ore", so they should be able to detect custom ores without any additional effort from the addon's developer.

Additionally, addon developers can apply the following block tags to blocks to make them get detected by dowsing rods:
- `dowsing:overworld_ore` - Birch Dowsing Rod
- `dowsing:geode_wall` - Dark Oak Dowsing Rod
- `dowsing:nether_ore` - Warped Dowsing Rod
- `dowsing:decorative_stone` - Cherry Dowsing Rod

Read the [Minecraft Bedrock Technical Wiki](https://wiki.bedrock.dev/blocks/block-tags.html) to see how to use block tags.

The mangrove dowsing rod detects any block not part of the "minecraft" namespace, so it should also work automatically.