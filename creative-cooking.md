---
title: Creative Cooking
nav_order: 2
---

# Creative Cooking
![Creative Cooking Thumbnail](/images/creativecooking/cc_0.png)

Creative Cooking is an addon that makes cooking food a creative process in Minecraft Bedrock Edition.

[Download](/creativecooking.mcaddon){: .btn } [Feedback and Bug Reports](https://docs.google.com/forms/d/e/1FAIpQLSeKr_PbqUBF1kBB8lWgr_bC1CY1TPUCAHrPu0u4AxsGWloGvQ/viewform){: .btn }

> By downloading this addon, you agree not to repost it and to follow the [license](/licensing.html)

> **Make sure you enable Holiday Creator Features and Additional Modding Capabilities before playing!**

[Watch my video explaining all of the features](https://youtu.be/sulms5fp2fI){: .btn }

## Crops
![Some of the crops in Creative Cooking growing](/images/creativecooking/cc_1.png)

This addon adds 7 new crops, which can be found in loot chests or by breaking Wild Bushes, which spawn around the world. Many of them grow in unique ways.
- Lettuce - works like vanilla crops
- Tomatoes - grows a bush, the top can be harvested when it turns red
- Rice - similar to tomatoes but must be planted in water
- Soybeans - works like vanilla crops, can be harvested in either wet form (which can be replanted but not cooked with) or dry form (which cannot be replanted but can be cooked with)
- Corn - same as tomatoes
- Crimson Chilis - similar to tomatoes but planted on Nylium or Netherrack
- Grapes - hang from the ceiling like glow berry vines, lower half can be harvested

> Make sure you plant the crops on hydrated farmland, there is currently a Bedrock Edition bug that makes custom crops not work on dry farmland.

Creative Cooking also adds Orchard Shears, which are special shears that upon breaking Oak or Cherry leaves, give you a much higher chance of getting the corresponding fruit.

There are also Stewed Shroomlights, which are a food item that can be made by cooking Shroomlights.

## Processing
![Some of the blocks used to process food items in Creative Cooking](/images/creativecooking/cc_2.png)

The millstone is used to convert grains (wheat, corn, rice) into flour more efficiently than the crafting table can. Flour is a new item used for several recipies. The vanilla bread recipe has been removed, instead flour can be put in a furnace to make bread. The millstone also converts sugarcane into sugar more efficiently than a crafting table.

The cooking pot is a crafting table that is used to craft hot items, like rice, soup, or pasta. It must be placed on top of a furnace, smoker, or campfire.

The meat slicer is used to turn cooked meat or meat alternatives into meat chunks and sliced meat (for sandwiches).

Mill Golems and Slicer Golems can also be crafted to automate those processes. Simply drop the corresponding item near the golem and it will be converted.

## Foods
All of the food in Creative Cooking consists of one or two base items that must be present, and then several different ingredients that can be added for customization. At the moment there is a maximum of two additional ingredients per food.

All hot foods (soup, rice, and pasta) are crafted in the cooking pot and give regeneration when eaten.

All sweet foods (juice, cookies, and pie) give speed when eaten.

All food containing carrots gives jump boost when eaten, and all food containing chilis deals a bit of damage but gives fire resistance when eaten.

### Soup
![Soup and its ingredients](/images/creativecooking/cc_3.png)

Soup is made in the cooking pot and requires a bowl as well as a broth item, either a tomato or a meat chunk. It can have carrots, potatoes, chilis, or meat chunks added.

### Rice and Pasta
![Rice, pasta, and their ingredients](/images/creativecooking/cc_4.png)

Rice is made in the cooking pot and requires a bowl and some rice as base items. It can have carrots, chilis, beetroots, meat chunks, or eggs added.

Pasta is made in the cooking pot and requires a bowl and some pasta, which is crafted from flour. It can have tomatoes, meat chunks, or cheese added. Cheese is crafted in the cooking pot from milk.

### Juice and Wine
![Juice, wine, and their ingredients](/images/creativecooking/cc_5.png)

Juice is made in the crafting table by combining a glass bottle, sugar, and one of the following fruit items: apple, cherry, melon, grape, sweet berry, glow berry, or stewed shroomlight.

Juice can then be put in the Aging Barrel to age it into wine. The dial on the front of the barrel indicates how much it has aged, but it can be taken out at any time. Each fruit gives a different effect, and the potency of the effect increases the longer it ages.

### Pie
Pie is made in the crafting table with the base item of a pie crust, which is crafted from flour, sugar, and an egg. It can have apples, cherries, grapes, sweet berries, glow berries, or stewed shroomlights added.

### Sandwiches and Salads
![Sandwiches, salad, and their ingredients](/images/creativecooking/cc_6.png)

Sandwiches are made in the crafting table from bread and sliced meat as base items. They can have tomato, lettuce, chilis, or cheese added.

Salad is made in the crafting table with a bowl and some lettuce as base items. It can have carrots, beetroots, tomatoes, or corn added.

### Cookies
![Cookies and their ingredients](/images/creativecooking/cc_7.png)

Cookie dough is made in the crafting table from flour and sugar, optionally also with chocolate to make chocolate dough. Sweet berries, glow berries, cherries, and chocolate can be added. The dough must then be cooked to turn it into a cookie.

Breaking cocoa pods now drops cocoa pods as an item, which need to be broken down into beans and then dried by cooking them. Dried cocoa beans can then be made into brown dye or combined with sugar to make chocolate.

## Compatibility
Creative Cooking does not use `player.json`, so it should be compatible with most other addons. Additionally, it uses the following item tags in recipes:
- `creativecooking:cheese`
- `creativecooking:cherry`
- `creativecooking:chili`
- `creativecooking:cooked_meat`
- `creativecooking:corn`
- `creativecooking:flour`
- `creativecooking:grain`
- `creativecooking:grape`
- `creativecooking:lettuce`
- `creativecooking:pasta`
- `creativecooking:pie_crust`
- `creativecooking:rice`
- `creativecooking:soybean`
- `creativecooking:tomato`

If you're an addon developer, feel free to use these tags in your addons so that your items can be used in Creative Cooking recipes. See the [Bedrock technical wiki](https://wiki.bedrock.dev/items/items-16.html#item-tags) for information about adding item tags.