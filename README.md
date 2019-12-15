## The Badlands Challenge

The oceans have boiled away, evaporated by a harsh sun.
Plants and animals are all but dead.
You pilfer old mineshafts to sustain your meager existence,
but you can't go on like this forever.
A distant jungle offers hope.

Welcome to **The Badlands Challenge**.

-----

The Badlands Challenge is a new way to play minecraft using the checkerboard feature of the game's buffet generation.

You spawn in a huge badlands biome that stretches infinitely to the northwest and southeast.
No passive mobs or trees spawn in badlands biomes,
so you'll need to collect wood and food from the abandoned mines that spawn on the surface of this biome.

To the northeast or southwest, after 9k blocks you'll find a thousand-block-wide desert,
the barren remains of a once thriving jungle.
At its far edge, a sliver of jungle still clings to existence.
Beyond that is a stretch of about 2.3k blocks that contains enough biomes to provide you with most resources.
There's shattered savanna, sunflower plains, flower forest, ice spikes, mushroom fields, and more.
All of the biomes are arranged in wide stripes that zig-zag from northwest to southeast.

**Rules**

* No sleeping until you reach the jungle
* No branch mining until you reach the jungle
* No going to the nether until you reach the jungle
* No switching out of hardcore until you reach the jungle

**How To Play**

* Create a buffet world in harcore mode
* Exit the game
* Locate the folder for the world you just created
* Use an NBT editor to change `generatorOptions` in `level.dat` to [this](https://raw.githubusercontent.com/DMBuce/badlands-challenge/master/generatorOptions.json). If your NBT editor is `nbted`, you can [copy and paste generatorOptions from here](https://raw.githubusercontent.com/DMBuce/badlands-challenge/master/generatorOptions.nbted).
* Optionally, back up `level.dat` so that you can just copy it to a new save if you die
* Delete all the files under the `region` folder
* Relaunch the game
* Open the world
* Head towards (10000, 10000) or (-10000, -10000)

Once you reach the jungle you can switch your world out of hardcore mode as a reward for completing the challenge.
To do that,

* Exit the game
* Edit `level.dat` like you did before and change `hardcore` to `0`

Good luck, have fun!

