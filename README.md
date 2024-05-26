# markkana
An unreal engine project decicated to old Finnish Markka. Please find the 3D models in Blender and Unreal formats in the [Meshes](https://github.com/nisipop/markkana/tree/main/Meshes) folder.

If you might think about markka licenses, the Finnish National Bank has announced the images of markka coins are free of copyright restrictions. Also, markka is obsolete currency, outdated completely.

The project also contains a couple of Unreal Blueprints that are free to use. The main blue print "BP_CoinSpawnerSpot_001.uasset" spawns static mesh actors at desired intervals, however, in this case you could spawn the coins in the project. Make your markka casino! Here's short introduction how the [blueprint coin spawner](https://github.com/nisipop/markkana/tree/main/Blueprints) works:

![MarkanaIntro](https://github.com/nisipop/markkana/assets/53601721/7db5c3b1-e56d-4374-a5f9-b62a3db0bb4d)


1) Initialize spawn, cleaning and stopping of spawning


![SpawnBeginPlay](https://github.com/nisipop/markkana/assets/53601721/abce85bb-9f32-414f-b036-30908c00925b)

2) The main spawning custom event


![SpawnMain](https://github.com/nisipop/markkana/assets/53601721/d55a8794-4642-45a0-b4ea-d9c53354b9bf)


3) The cleanup custom event and function


![SpawnClean](https://github.com/nisipop/markkana/assets/53601721/0af18ba9-e56a-4b6e-98cb-ae4832ad788a)

![CoinDestructFunction](https://github.com/nisipop/markkana/assets/53601721/1095ecb1-d942-4f63-8444-23a351a314af)


5) Stop spawn


![StopSpawn](https://github.com/nisipop/markkana/assets/53601721/23a8fb01-09c9-4bd7-8b98-ccbf0793504a)


