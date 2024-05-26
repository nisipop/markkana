# markkana
An unreal engine project decicated to old Finnish Markka. Please find the 3D models in Blender and Unreal formats in the /Meshes folder.

If you might think about markka licenses, the Finnish National Bank has announced the images of Markka are free of copyright restrictions. Also, markka is obsolete currency, outdated completely.

The project also contains a couple of Unreal Blueprints that are free to use. The main blue print "BP_CoinSpawnerSpot_001.uasset" spawns static mesh actors at desired intervals, however, in this case you could spawn the coins in the project. Make your markka casino! Here's short introduction how the blueprint works:

1) Initialize spawn, cleaning and stopping of spawning

https://github.com/nisipop/markkana/blob/main/BlueprintScreenshots/SpawnBeginPlay.PNG?raw=true

2) The main spawning custom event
https://github.com/nisipop/markkana/blob/main/BlueprintScreenshots/SpawnMain.PNG?raw=true

3) The cleanup custom event and function


https://github.com/nisipop/markkana/blob/main/BlueprintScreenshots/SpawnClean.PNG?raw=true
https://github.com/nisipop/markkana/blob/main/BlueprintScreenshots/CoinDestructFunction.PNG?raw=true

4) Stop spawn
https://github.com/nisipop/markkana/blob/main/BlueprintScreenshots/StopSpawn.PNG?raw=true

