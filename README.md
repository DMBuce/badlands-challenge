## The Badlands Challenge

The oceans have boiled away, evaporated by a harsh sun.
Plants and animals are all but dead.
You pilfer old mineshafts to sustain your meager existence,
but you can't go on like this forever.
A distant jungle offers hope.

Welcome to **The Badlands Challenge**.

-----

The Badlands Challenge is a new way to play Minecraft Java Edition using the checkerboard feature of the game's buffet generation.

You spawn in a huge badlands biome that stretches infinitely to the northeast and southwest.
No passive mobs or trees spawn in badlands biomes,
so you'll need to collect wood and food from the abandoned mines that spawn on the surface of this biome.

To the northwest or southeast, after 9k blocks you'll find a thousand-block-wide desert,
the barren remains of a once thriving jungle.
At its far edge, a sliver of jungle still clings to existence.
Beyond that is a stretch of about 2k blocks that contains enough biomes to provide you with most resources.
There's shattered savanna, sunflower plains, flower forest, ice spikes, mushroom fields, and more.
All of the biomes are arranged in wide stripes that zig-zag from northeast to southwest.

**Rules**

* No sleeping until you reach the jungle
* No branch mining until you reach the jungle
* No going to the nether until you reach the jungle
* No switching out of hardcore until you reach the jungle

**How To Play**

* Create a buffet world in harcore mode.
* Exit the game.
* Locate the folder for the world you just created. It will be in the `saves` subdirectory of your [minecraft folder](https://help.mojang.com/customer/portal/articles/1480874-where-are-minecraft-files-stored-).
* Change `generatorOptions` in your `level.dat` file
  * Use an NBT editor to change `generatorOptions` to [this](https://raw.githubusercontent.com/DMBuce/badlands-challenge/master/generatorOptions.json).
  * If your NBT editor is `nbted`, you can [copy and paste generatorOptions from here](https://raw.githubusercontent.com/DMBuce/badlands-challenge/master/generatorOptions.nbted).
  * If you don't know how to use an NBT editor and don't care about generating your own seed, you can [download this level.dat file](https://raw.githubusercontent.com/DMBuce/badlands-challenge/master/level.dat) and use it instead.
* Optionally, back up `level.dat` so that you can just copy it to a new save if you die.
* Delete all the files under the `region` folder.
* Relaunch the game.
* Open the world.
* Head towards (10000, 10000) or (-10000, -10000) .

Once you reach the jungle you can switch your world out of hardcore mode as a reward for completing the challenge.
To do that,

* Exit the game
* Edit `level.dat` like you did before and change `hardcore` to `0`

Good luck, have fun!

**Update 2020-04-03**

It turns out that chests in shipwrecks don't generate with a treasure map in them like they normally do.
This is because there are no beach biomes near ocean biomes.
As a workaround, you can install the [No Treasure Maps](https://github.com/DMBuce/badlands-challenge/blob/master/no_treasure_maps.zip) datapack.

