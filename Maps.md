# atomic_heart_uetools

## Maps

### Travel command

To travel to a map, use the command:

    travel MAP_NAME

For example:

    travel LQA_Test

### Load Level Instance command

To load a level instance (sublevel), use the command:

    UETools_LoadLevelInstance MAP_PATH

For example:

    UETools_LoadLevelInstance AtomicHeart/Content/DLC2/Maps/World/Climb2/UEDPIE_1_Climb_Level2_DLC2

## Table of maps:

### Test Maps/Тестовые карты

| Map name/Название карты      |                  Command/Команда                                   | Comment/Комментарий         |
|:-----------------------------|:------------------------------------------------------------------:|:----------------------------|
| LQA Test/Тест LQA            | travel LQA_Test                                                    | Main game test map          |
| LQA Test DLC1/Тест LQA DLC1  | travel LQA_Test_DLC1                                               | DLC1 test map               |
| LQA Test DLC2/Тест LQA DLC2  | travel LQA_Test_DLC2                                               | DLC2 test map               |
| Flatgrass Lighting           | travel Flatgrass_Lighting                                          | Lighting test map           |
| TechDesign Map Quest         | travel TechDesign_Map_quest                                        | Quest design test map       |

### Polygons/Полигоны

Testing grounds that exist in the game. Some are available, some are in development.

**Available Polygons/Доступные полигоны:** 1, 2, 6, 8, 9, 10, 11, 12

**In Development/В разработке:** 3, 4, 5, 7, 13, 14, 15, 16

| Map name/Название карты      |                  Command/Команда                                   | Comment/Комментарий         |
|:-----------------------------|:------------------------------------------------------------------:|:----------------------------|
| Polygon 3                    | UETools_LoadLevelInstance AtomicHeart/Content/Maps/Worlds/Atomic_World_01/Indoor/Polygons/Polygon_3_Volumetric.umap | In development |
| Polygon 4                    | UETools_LoadLevelInstance AtomicHeart/Content/Maps/Worlds/Atomic_World_01/Indoor/Polygons/Polygon_4_Volumetric.umap | In development |
| Polygon 5                    | UETools_LoadLevelInstance AtomicHeart/Content/Maps/Worlds/Atomic_World_01/Indoor/Polygons/Polygon_5.umap | In development |
| Polygon 7                    | UETools_LoadLevelInstance AtomicHeart/Content/Maps/Worlds/Atomic_World_01/Indoor/Polygons/Polygon_7_Volumetric.umap | In development |
| Polygon 13                   | UETools_LoadLevelInstance AtomicHeart/Content/Maps/Worlds/Atomic_World_01/Indoor/Polygons/Polygon_13_Volumetric.umap | In development |
| Polygon 14                   | UETools_LoadLevelInstance AtomicHeart/Content/Maps/Worlds/Atomic_World_01/Indoor/Polygons/Polygon_14_Volumetric.umap | In development |
| Polygon 15                   | UETools_LoadLevelInstance AtomicHeart/Content/Maps/Worlds/Atomic_World_01/Indoor/Polygons/Polygon_15.umap | In development |
| Polygon 16                   | UETools_LoadLevelInstance AtomicHeart/Content/Maps/Worlds/Atomic_World_01/Indoor/Polygons/Polygon_16.umap | In development |

### DLC2 Maps/Карты DLC2

| Map name/Название карты      |                  Command/Команда                                   | Comment/Комментарий         |
|:-----------------------------|:------------------------------------------------------------------:|:----------------------------|
| Climb Level 2/Уровень лазания 2 | UETools_LoadLevelInstance AtomicHeart/Content/DLC2/Maps/World/Climb2/UEDPIE_1_Climb_Level2_DLC2 |          |
| Goose Runner Rails/Гонки с гусем рельсы | UETools_LoadLevelInstance AtomicHeart/Content/DLC2/Maps/World/GooseRunner/GooseRunner_Sections_RailsMode_1 | |
| Goose Runner Slide/Гонки с гусем скольжение | UETools_LoadLevelInstance AtomicHeart/Content/DLC2/Maps/World/GooseRunner/GooseRunner_Sections_SlideMode_1 | |

### Vavilov Dungeon/Подземелье Вавилова

| Map name/Название карты      |                  Path/Путь                                         | Comment/Комментарий         |
|:-----------------------------|:------------------------------------------------------------------:|:----------------------------|
| Vavilov Lab/Лаборатория Вавилова | AtomicHeart/Content/Maps/Worlds/Atomic_World_01/Indoor/Vavilov/Vavilov_Dungeon/Vavilov_Laba.umap |       |
