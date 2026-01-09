# atomic_heart_uetools

## Objects

To summon some object, use the command:

    UETools_SoftSummon CLASS_FULL_PATH..

For example:

    UETools_SoftSummon AtomicHeart/Content/Core/AI/Characters/Plyush/BP_PlychCharacter..

Please don't forget to put two dots `..` after class path

### Table of objects:

| Object name/Название объекта |                  Class path/Путь к классу                         | Comment/Комментарий         |
|:-----------------------------|:-----------------------------------------------------------------:|:----------------------------|
| **BOSSES/БОССЫ**             |                                                                   |                             |
| Natasha/Наташа               | /Game/Core/AI/Characters/Natasha/BP_NatashaCharacter..            | Boss                        |
| Natasha Small/Наташа малая   | /Game/Core/AI/Characters/Natasha/BP_NatashaSmallCharacter..       | Boss variant                |
| Belyash/Беляш                | /Game/Core/AI/Characters/Belyash/BP_BelyashCharacter..            | Boss                        |
| Belyash VDNH/Беляш ВДНХ      | /Game/Core/AI/Characters/Belyash/BP_BelyashCharacterVDNH..        | Boss variant                |
| Belyash Small/Беляш маленький | /Game/Core/AI/Characters/Belyash/BP_BelyashSmall_Character..     | Boss variant                |
| Ejiha (Hedgie)/Ежиха         | /Game/Core/AI/Characters/Ejiha/BP_EjihaCharacter..                | Boss (buggy)                |
| Rosa (Dewdrop)/Роза          | /Game/Core/AI/Characters/Rosa/BP_RosaCharacter..                  | Boss                        |
| Twins/Близняшки              | /Game/Core/AI/Characters/Twins/BP_TwinsCharacter..                | Boss (buggy)                |
| Twins First Fight/Близняшки 1 бой | /Game/Core/AI/Characters/Twins/BP_TwinsCharacter_FirstFight.. | Boss variant                |
| Twins Second Fight/Близняшки 2 бой | /Game/Core/AI/Characters/Twins/BP_TwinsCharacter_SecondFight.. | Boss variant             |
| Twins Left/Близняшка левая   | /Game/Core/AI/Characters/Twins/BP_TwinsCharacter_Left..           | Boss variant                |
| Twins Right/Близняшка правая | /Game/Core/AI/Characters/Twins/BP_TwinsCharacter_Right..          | Boss variant                |
| Busa Boss (Colossus BEA-D)/Буса Босс | /Game/DLC/Core/AI/Characters/Busa/Boss/BP_Busa_Boss_Character.. | Boss DLC#1          |
| **ENEMIES/ВРАГИ**            |                                                                   |                             |
| Plyusch (Ivy)/Плющ           | /Game/Core/AI/Characters/Plyush/BP_PlychCharacter..               |                             |
| Plyusch Symbiosis/Плющ симбиоз | /Game/Core/AI/Characters/Plyush/BP_PlychCharacterSymbiosis..    | Variant                     |
| Vov (VOV-A6)/ВОВ             | /Game/Core/AI/Characters/Vov/BP_VovCharacter..                    | Lab Tech                    |
| Vov Shield/ВОВ со щитом      | /Game/Core/AI/Characters/Vov/BP_VovShieldCharacter..              |                             |
| Vov Fast (Black)/ВОВ быстрый | /Game/Core/AI/Characters/Vov/BP_VovCharacter_Fast..              |                             |
| Vov Black Burned/ВОВ сгоревший | /Game/Core/AI/Characters/Vov/BP_VovBlackBurned_Cutscene..       | Cutscene                    |
| Vov Simple/ВОВ простой       | /Game/Core/AI/Characters/Vov/BP_VovCharacter_Simple..             | Test variant                |
| Medic (MED-9)/Медик          | /Game/Core/AI/Characters/Medic/BP_MedicCharacter..                |                             |
| Raf (RAF-9 Engineer)/Раф     | /Game/Core/AI/Characters/Raf/BP_RafCharacter..                    | Engineer                    |
| Raf Treadmill/Раф на дорожке | /Game/Core/AI/Characters/Raf/BP_RafCharacter_Treadmill..          | Variant                     |
| Raf Waiter/Раф официант      | /Game/Core/AI/Characters/Raf/BP_RafCharacter_Waiter..             | Variant                     |
| Matka (Mother)/Матка         | /Game/Core/AI/Characters/Matka/BP_MatkaCharacter..                |                             |
| Mutant/Мутант                | /Game/Core/AI/Characters/Mutant/BP_MutantCharacter..              |                             |
| Mutant Base/Мутант базовый   | /Game/Core/AI/Characters/Mutant/BP_MutantCharacter_Base..         |                             |
| Mutant Base Child/Мутант маленький | /Game/Core/AI/Characters/Mutant/BP_MutantCharacter_Base_Child.. |                           |
| Mutant Acid/Мутант кислотный | /Game/Core/AI/Characters/Mutant/BP_MutantCharacter_Acid..         |                             |
| Mutant Soldier/Мутант солдат | /Game/Core/AI/Characters/Mutant/BP_MutantSoldierCharacter..       |                             |
| Mutant Nurse/Мутант медсестра | /Game/Core/AI/Characters/Mutant/BP_MutantNurseCharacter..        |                             |
| Mutant Big Basic/Большой мутант | /Game/Core/AI/Characters/Mutant/MutantBig/BP_MutantBigBasicCharacter.. |                     |
| Mutant Big Acid/Большой кислотный | /Game/Core/AI/Characters/Mutant/MutantBig/BP_MutantBigAcidCharacter.. |                    |
| Mutant Big Fire/Большой огненный | /Game/Core/AI/Characters/Mutant/MutantBig/BP_MutantBigFireCharacter.. |                     |
| Pchela (WSP-9)/Пчела         | /Game/Core/AI/Characters/Bee/BP_PchelaCharacter..                 |                             |
| Pchela Camera/Пчела камера   | /Game/Core/AI/Characters/Bee/CameraBee/BP_CameraPchela..          |                             |
| Pchela Patrolling Camera/Пчела патруль | /Game/Core/AI/Characters/Bee/CameraBee/BP_PatrollingCameraPchela.. |                  |
| Pchela Laser/Пчела лазер     | /Game/Core/AI/Characters/Bee/LaserPchela/BP_LaserPchelaCharacter.. |                           |
| Pchela Smoke/Пчела дым       | /Game/Core/AI/Characters/Bee/SmokePchela/BP_SmokePchelaCharacter.. |                           |
| Drofa/Дрофа                  | /Game/Core/AI/Characters/Drofa/BP_DrofaCharacter..                |                             |
| Drofa Child Flying/Дрофа маленький летающий | /Game/Core/AI/Characters/Drofa/BP_DrofaCharacter_Child_Flying.. |                   |
| Drofa Child Static/Дрофа маленький статичный | /Game/Core/AI/Characters/Drofa/BP_DrofaCharacter_Child_Static.. |                  |
| Drofa Telekinetic/Дрофа телекинетик | /Game/Core/AI/Characters/Drofa/BP_Drofa_Telekinetic..        |                             |
| Sipuha/Сипуха                | /Game/Core/AI/Characters/Sipuha/BP_SipuhaCharacter..              |                             |
| Sipuha Child/Сипуха маленький  | /Game/Core/AI/Characters/Sipuha/BP_SipuhaCharacter_Child..        |                             |
| Sipuha Holo/Сипуха голограмма | /Game/Core/AI/Characters/Sipuha/BP_SipuhaCharacter_Holo..        |                             |
| Sipuha Rocket/Сипуха ракета  | /Game/Core/AI/Characters/Sipuha/BP_SipuhaRocketCharacter..        |                             |
| Sipuha Laser/Сипуха лазер    | /Game/Core/AI/Characters/Sipuha/BP_SipuhaLaserCharacter..         |                             |
| Shmel/Шмель                  | /Game/Core/AI/Characters/Shmel/BP_Base_ShmelCharacter..           |                             |
| Pobeg (Sprout)/Побег         | /Game/Core/AI/Characters/Pobeg/BP_PobegCharacter..                |                             |
| Pobeg for Matka/Побег для Матки | /Game/Core/AI/Characters/Pobeg/BP_PobegCharacterForMatkaSpawn.. |                           |
| Pobeg for Matka Fast/Побег быстрый | /Game/Core/AI/Characters/Pobeg/BP_PobegCharacterForMatkaSpawnfast.. |                     |
| Pobeg Big/Побег большой      | /Game/Core/AI/Characters/Pobeg/BP_PobegBigCharacter..             |                             |
| Pobeg Big for Matka/Побег большой для Матки | /Game/Core/AI/Characters/Pobeg/BP_PobegBigCharacterForMatka.. |                    |
| RotoRobot (ARU-31/6)/Роторобот | /Game/Core/AI/Characters/RotoRobot/BP_RotoRobotCharacter..      |                             |
| Chicken/Курица               | /Game/Core/AI/Characters/Chicken/BP_ChickenCharacter..            | Livestock                   |
| Utka (Duck)/Утка             | /Game/Core/AI/Characters/Chicken/BP_UtkaCharacter..               | Livestock                   |
| Dandelion Camera/Одуванчик   | /Game/Core/AI/Characters/Camera/BP_CCTV_Camera..                  | Security Camera             |
| Dandelion OpenWorld/Одуванчик ОМ | /Game/Core/AI/Characters/Camera/BP_CCTV_Camera_OpenWorld..    | Security Camera             |
| Vatrushka Turret/Ватрушка    | /Game/Core/AI/Characters/Vatrushka_Turret/BP_VatrushkaTurretCharacter.. | Turret                |
| Vatrushka Flamethrower/Ватрушка огнемёт | /Game/Core/AI/Characters/Vatrushka_Turret/BP_VatrushkaTurretCharacter_Flamethrower.. | |
| Vatrushka Laser/Ватрушка лазер | /Game/Core/AI/Characters/Vatrushka_Turret/BP_VatrushkaTurretCharacter_Laser.. |              |
| Turret/Турель                | /Game/Core/AI/Characters/Turret/BP_Turret..                       |                             |
| Turret White/Турель белая    | /Game/Core/AI/Characters/Turret/BP_Turret_White..                 |                             |
| **DLC1 Enemies/DLC1 Враги**  |                                                                   |                             |
| Goose/Гусь                   | /Game/DLC/Core/AI/Characters/GOOSE/BP_Goose_Character..           | DLC #1                      |
| Maniken (M4D-5 Dummy)/Манекен | /Game/DLC/Core/AI/Characters/Maniken/BP_ManikenCharacter..      | DLC #1                      |
| Busa Single (BEA-D)/Буса     | /Game/DLC/Core/AI/Characters/Busa/BP_Busa_Single_Character..      | DLC #1                      |
| Busa Blue/Буса синяя         | /Game/DLC/Core/AI/Characters/Busa/BP_Busa_Single_Character_Colored_Blue.. | DLC #1             |
| Busa Dog (BEA-D Duo)/Буса пёс | /Game/DLC/Core/AI/Characters/Busa/BP_Busa_Dog_Character..       | DLC #1                      |
| Busa Centaur (BEA-D Trio)/Буса Кентавр | /Game/DLC/Core/AI/Characters/Busa/BP_Busa_Centaur_Character.. | DLC #1                  |
| **NPC/НПЦ**                  |                                                                   |                             |
| Human NPC/Человек            | /Game/Core/AI/Characters/Human/BP_NPCHuman..                      |                             |
| Human Female 02/Женщина 02   | /Game/Core/AI/Characters/Human/BP_NPCHuman_Female02..             |                             |
| Human Male 01/Мужчина 01     | /Game/Core/AI/Characters/Human/BP_NPCHuman_Male01..               |                             |
| Larisa/Лариса                | /Game/Core/AI/Characters/Larisa/BP_NPC_Larisa..                   |                             |
| Lebedev/Лебедев              | /Game/DLC/Core/AI/Characters/Lebedev/BP_LebedevNPCCharacter..     | DLC                         |
| Tereshkova Robot/Терешкова   | /Game/Core/AI/Characters/Tereshkova/BP_NPC_TereshkovaRobot..      |                             |
| Tereshkova Clara/Терешкова Клара | /Game/Core/AI/Characters/Tereshkova/BP_NPC_TereshkovaRobot_Clara.. |                         |
| NPC Vov/НПЦ ВОВ              | /Game/Core/AI/Characters/Vov/BP_NPCVov1..                         |                             |
| Test Target Enemy/Тест мишень | /Game/Core/AI/Characters/Test/BP_TestTargetEnemy..               | Test                        |
| Farcovshik/Фарцовщик         | /Game/Core/AI/Characters/Farcovshik/BP_NPC_Farcovshik..           |                             |
| **Animals/Животные**         |                                                                   |                             |
| Pig/Свинья                   | /Game/Core/AI/Animals/Pig/BP_PigAnimalCharacter..                 | Livestock                   |
| Pig Cage/Свинья в клетке     | /Game/Core/AI/Animals/Pig/BP_PigCageAnimalCharacter..             | Livestock                   |
| Cow/Корова                   | /Game/Core/AI/Animals/Cow/BP_CowAnimalCharacter..                 | Livestock                   |
| **Melee Weapons/Оружие ближнего боя** |                                                         |                             |
| Axe/Топор                    | AtomicHeart/Content/Core/Objects/Items/BP_Pickupable_Axe..        |                             |
| Bober/Бобёр                  | AtomicHeart/Content/Core/Objects/Items/BP_Pickupable_Bober..      |                             |
| Hipar/Хипар                  | AtomicHeart/Content/Core/Objects/Items/BP_Pickupable_Hipar..      |                             |
| Hirurg/Хирург                | AtomicHeart/Content/Core/Objects/Items/BP_Pickupable_Hirurg..     |                             |
| Karusel/Карусель             | AtomicHeart/Content/Core/Objects/Items/BP_Pickupable_Hirurg..     | Path might be incorrect     |
| Kilka/Килька                 | AtomicHeart/Content/Core/Objects/Items/BP_Pickupable_Kilka..      |                             |
| Klusha/Клуша                 | AtomicHeart/Content/Core/Objects/Items/BP_Pickupable_Petuh..      | DLC #1                      |
| Lapta/Лапта                  | AtomicHeart/Content/Core/Objects/Items/BP_Pickupable_Lapta..      |                             |
| Lisa/Лиса (Fox)              | AtomicHeart/Content/Core/Objects/Items/BP_Pickupable_Lisa..       |                             |
| Lumberjack/Лесоруб           | AtomicHeart/Content/Core/Objects/Items/BP_Pickupable_Binoculars.. |                             |
| Neptune/Нептун               | AtomicHeart/Content/Core/Objects/Items/BP_Pickupable_Neptun..     |                             |
| Pashtet/Паштет               | AtomicHeart/Content/Core/Objects/Items/BP_Pickupable_Pashtet..    |                             |
| Petuh/Петух                  | AtomicHeart/Content/Core/Objects/Items/BP_Pickupable_Petuh..      |                             |
| Sguschenka/Сгущёнка          | AtomicHeart/Content/Core/Objects/Items/BP_Pickupable_Sguschenka.. |                             |
| Shved/Швед (Swede)           | AtomicHeart/Content/Core/Objects/Items/BP_Pickupable_Shved..      |                             |
| Snejok/Снежок (Snowball)     | AtomicHeart/Content/Core/Objects/Items/BP_Pickupable_Snejok..     |                             |
| Thunderclap/Громовержец      | AtomicHeart/Content/Core/Objects/Items/BP_Pickupable_Gromoverzhec.. | DLC #3                   |
| Zvezdochka/Звёздочка         | AtomicHeart/Content/Core/Objects/Items/BP_Pickupable_Zvezdochka.. | DLC #1                      |
| **Range Weapons/Дальнобойное оружие** |                                                         |                             |
| AK-47/АК-47 (Kalash)         | AtomicHeart/Content/Core/Objects/Items/BP_Pickupable_AK47_MagazineAttached.. |                  |
| Bidonist/Бидонист            | AtomicHeart/Content/Core/Objects/Items/BP_Pickable_Ammo_Cigarets.. |                           |
| Carbine/Карабин              | AtomicHeart/Content/Core/Objects/Items/BP_Pickable_Carbine..      |                             |
| Debug Gun/Отладочный пистолет | AtomicHeart/Content/Core/Objects/Items/BP_Pickupable_DebugGun..  | Debug/Test only             |
| Dominator/Доминатор          | AtomicHeart/Content/Core/Objects/Items/BP_Pickupable_Dominator..  |                             |
| Electro/Электро (Energy Pistol) | AtomicHeart/Content/Core/Objects/Items/BP_Pickupable_Electro.. |                             |
| Krepysh/Крепыш (Fat Boy/Rocket Launcher) | AtomicHeart/Content/Core/Objects/Items/BP_Pickupable_Krepysh.. |               |
| KS-23/КС-23 (Shotgun)        | AtomicHeart/Content/Core/Objects/Items/BP_Pickupable_ShotgunKS23.. |                            |
| Kuzmich/Кузьмич (Auto Shotgun) | AtomicHeart/Content/Core/Objects/Items/BP_Pickupable_Kuzmich.. | DLC #3                      |
| Plasma Gun/Плазменный пистолет | /Game/DLC/Core/Weapons/Range/Plasmagun/BP_Pickupable_Plasmagun.. | DLC #1                   |
| PM/ПМ (Pistol)               | AtomicHeart/Content/Core/Objects/Items/BP_Pickupable_PM..         |                             |
| Railgun/Рельсотрон           | AtomicHeart/Content/Core/Objects/Items/BP_Pickupable_Railgun..    |                             |
| **Ammo/Патроны**             |                                                                   |                             |
| Pistol Ammo Single/Одиночный патрон ПМ | AtomicHeart/Content/Core/Objects/Items/BP_Pickupable_PM_Ammo_Single.. | x1 cartridge          |
| Pistol Ammo Box/Коробка патронов ПМ | AtomicHeart/Content/Core/Objects/Items/BP_Pickupable_PM_Ammo_Box.. | x9 cartridges            |
| Shotgun Ammo Single/Одиночный патрон дробовик | AtomicHeart/Content/Core/Objects/Items/BP_Pickupable_Shotgun_Ammo_single.. | x1 shell |
| Shotgun Ammo Magazine/Магазин дробовик | AtomicHeart/Content/Core/Objects/Items/BP_Pickupable_Shotgun_Ammo_Magazine.. | x5 shells      |
| AK-47 Ammo Magazine/Магазин АК-47 | AtomicHeart/Content/Core/Objects/Items/BP_Pickupable_AK47_Ammo_Magazine.. | x30 cartridges       |
| Rocket Ammo Single/Одиночная ракета | AtomicHeart/Content/Core/Objects/Items/BP_Pickupable_Krepysh_Ammo_Single.. | x1 rocket         |
| Plasma Gun Ammo/Патроны плазмаган | /Game/DLC/Core/Weapons/Range/Plasmagun/BP_Pickupable_Plasmagun_Ammo.. | DLC #1              |
| **Cassette Modules/Кассетные модули** |                                                        |                             |
| Cassette Electric/Электро кассета | AtomicHeart/Content/Core/Objects/Items/Cassettes/BP_Pickable_CassetteElectricity.. |          |
| Cassette Fire/Огненная кассета | AtomicHeart/Content/Core/Objects/Items/Cassettes/BP_Pickable_Cassette_Fire.. |                 |
| Cassette Frost/Морозная кассета | AtomicHeart/Content/Core/Objects/Items/Cassettes/BP_Pickable_Cassette_Frost.. |               |
| **Resources/Ресурсы**        |                                                                   |                             |
| Metal Parts/Металлические детали | AtomicHeart/Content/Core/Objects/Items/Resourses/Common_Resources/BP_Pickupable_Metal_Parts.. | Common/Обычный |
| Synthetic Material/Синтетический материал | AtomicHeart/Content/Core/Objects/Items/Resourses/Common_Resources/BP_Pickable_Synthetic_Material_Resource.. | Common/Обычный |
| Biomaterial/Биоматериал      | AtomicHeart/Content/Core/Objects/Items/Resourses/Common_Resources/BP_Pickable_Resource_Biomaterial.. | Common/Обычный |
| Superconductor/Сверхпроводник | AtomicHeart/Content/Core/Objects/Items/Resourses/Uncommon_Resources/BP_Pickupable_Resource_Superconductor.. | Uncommon/Необычный |
| Chemicals/Химикаты           | AtomicHeart/Content/Core/Objects/Items/Resourses/Uncommon_Resources/BP_Pickupable_Resources_Chemicals.. | Uncommon/Необычный |
| Energy Cell/Энергоячейка     | AtomicHeart/Content/Core/Objects/Items/Resourses/Rare_Resources/BP_Pickupable_Energy_Cell_Resource.. | Rare/Редкий |
| Microelectronics/Микроэлектроника | AtomicHeart/Content/Core/Objects/Items/Resourses/Rare_Resources/BP_Pickupable_Resource_Microelectronics.. | Rare/Редкий |
| Neural Module/Нейромодуль    | AtomicHeart/Content/Core/Objects/Items/Resourses/Legendary_Resources/BP_Pickupable_NeuralModule.. | Legendary/Легендарный |
| **Consumables/Расходники**   |                                                                   |                             |
| Adrenalin/Адреналин          | AtomicHeart/Content/Core/Objects/Items/Consumables/Pickable/BP_Pickable_adrenalin.. |          |
| Aid Big/Большая аптечка      | AtomicHeart/Content/Core/Objects/Items/Consumables/Pickable/BP_Pickable_consumable_aid_big.. |  |
| Aid Medium/Средняя аптечка   | AtomicHeart/Content/Core/Objects/Items/Consumables/Pickable/BP_Pickable_consumable_aid_big.. | Uses same path  |
| Capsule Jelly/Желе в капсуле | AtomicHeart/Content/Core/Objects/Items/BP_Pickable_CapsuleJelly.. |                             |
| Cigarettes/Сигареты          | AtomicHeart/Content/Core/Objects/Items/BP_Pickable_Cigarettes..   |                             |
| Energetic/Энергетик (Dynamo) | AtomicHeart/Content/Core/Objects/Items/Consumables/Pickable/BP_Pickable_energetic.. |          |
| Meldonium/Мельдоний          | AtomicHeart/Content/Core/Objects/Items/Consumables/Pickable/BP_Pickable_meldonium.. |          |
| Sguschenka/Сгущёнка          | AtomicHeart/Content/Core/Objects/Items/Consumables/Pickable/BP_Pickable_sguschenka.. |         |
| Vodka/Водка                  | AtomicHeart/Content/Core/Objects/Items/Consumables/Pickable/BP_Pickable_vodka.. |               |
| **Weapon Recipes/Рецепты оружия** |                                                              |                             |
| AK-47 Recipe/Рецепт АК-47    | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/BP_Pickable_Ak47_Recipe.. |                 |
| PM Recipe/Рецепт ПМ          | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/BP_Pickable_PM_Recipe.. |                   |
| Electro Recipe/Рецепт Электро | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/BP_Pickable_Electro_Recipe.. |              |
| Krepysh Recipe/Рецепт Крепыш | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/BP_Pickable_Krepysh_Recipe.. |              |
| Railgun Recipe/Рецепт Рельсотрон | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/BP_Pickable_Railgun_Recipe.. |          |
| Zvezdochka Recipe/Рецепт Звёздочка | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/BP_Pickable_Zvezdochka_Recipe.. |      |
| Dominator Recipe/Рецепт Доминатор | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/BP_Pickable_Dominator_Recipe.. |        |
| Lisa Recipe/Рецепт Лиса      | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/BP_Pickable_Lisa_Recipe.. |                 |
| Pashtet Recipe/Рецепт Паштет | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/BP_Pickable_Pashtet_Recipe.. |              |
| Snejok Recipe/Рецепт Снежок  | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/BP_Pickable_Snejok_Recipe.. |               |
| Ammo Weak Recipe/Рецепт слабых патронов | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/BP_Pickable_Ammo_Weak_Recipe.. |   |
| Bidonist Recipe/Рецепт Бидонист | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/BP_Pickable_Bidonist_Recipe.. |          |
| Binoculars Recipe/Рецепт Бинокль | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/BP_Pickable_Binoculars_Recipe.. |        |
| Hipar Recipe/Рецепт Хипар    | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/BP_Pickable_Hipar_Recipe.. |                |
| Karusel Recipe/Рецепт Карусель | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/BP_Pickable_Karusel_Recipe.. |            |
| KS-23 Recipe/Рецепт КС-23    | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/BP_Pickable_KS23_Recipe.. |                 |
| Machinegun Ammo Recipe/Рецепт патронов пулемёта | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/BP_Pickable_MachinegunAmmo_Recipe.. | |
| Neptun Recipe/Рецепт Нептун  | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/BP_Pickable_Neptun_Recipe.. |               |
| Plasma Gun Recipe/Рецепт Плазмаган | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/BP_Pickable_Plasmagun_Recipe.. | DLC #1      |
| Shotgun Recipe/Рецепт Дробовик | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/BP_Pickable_Shotgun_Recipe.. |            |
| Small Aid Recipe/Рецепт малой аптечки | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/BP_Pickable_SmallAid_Recipe.. |    |
| **Cassette Recipes/Рецепты кассет** |                                                              |                             |
| Fire Cassette/Огненная кассета | AtomicHeart/Content/Core/Objects/Items/Cassettes/BP_Pickable_Cassette_Fire_Recipe.. |          |
| Frost Cassette/Морозная кассета | AtomicHeart/Content/Core/Objects/Items/Cassettes/BP_Pickable_Cassette_Frost_Recipe.. |        |
| Electricity Cassette/Электро кассета | AtomicHeart/Content/Core/Objects/Items/Cassettes/BP_Pickable_Cassette_Electricity_Recipe.. | |
| **Consumable Recipes/Рецепты расходников** |                                                    |                             |
| Adrenalin Recipe/Рецепт Адреналин | AtomicHeart/Content/Core/Objects/Items/Consumables/Recipes/Pickable/BP_Pickable_adrenalin_Recipe.. | |
| Energetic Recipe/Рецепт Энергетик | AtomicHeart/Content/Core/Objects/Items/Consumables/Recipes/Pickable/BP_Pickable_energetic_Recipe.. | |
| Meldonium Recipe/Рецепт Мельдоний | AtomicHeart/Content/Core/Objects/Items/Consumables/Recipes/Pickable/BP_Pickable_meldonium_Recipe.. | |
| Medium Aid Recipe/Рецепт средней аптечки | AtomicHeart/Content/Core/Objects/Items/Consumables/Recipes/Pickable/BP_Pickable_aid_medium_Recipe.. | |
| Big Aid Recipe/Рецепт большой аптечки | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/BP_Pickable_BigAid_Recipe.. |      |
| **Ammo Recipes/Рецепты патронов** |                                                               |                             |
| AK-47 Ammo/Патроны АК-47     | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/BP_Pickable_AK47Ammo_Recipe.. |             |
| Pistol Ammo/Пистолетные патроны | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/BP_Pickable_PistolAmmo_Recipe.. |         |
| Plasma Gun Ammo/Патроны плазмагана | /Game/DLC/Core/Weapons/Range/Plasmagun/DA_Item_PlasmagunAmmo_Recipe.. | DLC #1              |
| Rocket Ammo/Ракетные снаряды | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/BP_Pickable_RocketAmmo_Recipe.. |           |
| Shotgun Ammo/Дробь           | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/BP_Pickable_ShotgunAmmo_Recipe.. |          |
| **AK-47 Upgrades/Улучшения АК-47** |                                                             |                             |
| AK Barrel AO/АК Ствол AO     | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/Upgrades/AK/BP_Pickable_AK_BarrelAO_Recipe.. |  |
| AK Barrel AR/АК Ствол AR     | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/Upgrades/AK/BP_Pickable_AK_BarrelAR_Recipe.. |  |
| AK Cassette/АК Кассета       | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/Upgrades/AK/BP_Pickable_AK_Cassete_Recipe.. |   |
| AK Fire Rate/АК Скорострельность | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/Upgrades/AK/BP_Pickable_AK_FireRate_Recipe.. | |
| AK Scope Capacity/АК Прицел ёмкость | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/Upgrades/AK/BP_Pickable_AK_Scope_Capacity_Recipe.. | |
| AK Scope RedDot/АК Коллиматор | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/Upgrades/AK/BP_Pickable_AK_Scope_RedDot_Recipe.. | |
| AK Scope Thermal/АК Тепловизор | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/Upgrades/AK/BP_Pickable_AK_Scope_Thermal_Recipe.. | |
| **Dominator Upgrades/Улучшения Доминатора** |                                                    |                             |
| Dominator AntiBlackHole/Доминатор Анти-ЧД | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/Upgrades/Dominator/BP_Pickable_Dominator_AntiBlackHole_Recipe.. | |
| Dominator Cassette/Доминатор Кассета | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/Upgrades/Dominator/BP_Pickable_Dominator_Cassete_Recipe.. | |
| Dominator CirclingBall/Доминатор Вращающийся шар | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/Upgrades/Dominator/BP_Pickable_Dominator_CirclicngBall_Recipe.. | |
| Dominator HommingBullets/Доминатор Самонаводящиеся | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/Upgrades/Dominator/BP_Pickable_Dominator_HommingBullets_Recipe.. | |
| Dominator ShotgunShot/Доминатор Дробь | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/Upgrades/Dominator/BP_Pickable_Dominator_ShotgunShot_Recipe.. | |
| Dominator Spooling/Доминатор Раскрутка | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/Upgrades/Dominator/BP_Pickable_Dominator_Spooling_Recipe.. | |
| **Electro Upgrades/Улучшения Электро** |                                                          |                             |
| Electro Cassette/Электро Кассета | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/Upgrades/Electro/BP_Pickable_Electro_Casset_Recipe.. | |
| Electro EmiImpulse/Электро ЭМИ | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/Upgrades/Electro/BP_Pickable_Electro_Electro_EmiImpulse_Recipe.. | |
| Electro Leashes/Электро Привязь | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/Upgrades/Electro/BP_Pickable_Electro_ElectroLeashes_Recipe.. | |
| Electro Stopping/Электро Остановка | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/Upgrades/Electro/BP_Pickable_Electro_Stopping_Recipe.. | |
| **Krepysh Upgrades/Улучшения Крепыша** |                                                          |                             |
| Krepysh 3Rockets/Крепыш 3 ракеты | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/Upgrades/Krepysh/BP_Pickable_Krepysh_3Rockets_Recipe.. | |
| Krepysh Cassette/Крепыш Кассета | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/Upgrades/Krepysh/BP_Pickable_Krepysh_Cassette_Recipe.. | |
| Krepysh HommingMissles/Крепыш Самонаводящиеся | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/Upgrades/Krepysh/BP_Pickable_Krepysh_HommingMissles_Recipe.. | |
| Krepysh PolymerPuddle/Крепыш Полимерная лужа | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/Upgrades/Krepysh/BP_Pickable_Krepysh_PolymerPuddle_Recipe.. | |
| Krepysh TrapRockets/Крепыш Ракеты-ловушки | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/Upgrades/Krepysh/BP_Pickable_Krepysh_TrapRockets_Recipe.. | |
| Krepysh LessSelfDamage/Крепыш Меньше самоурона | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/Upgrades/Krepysh/BP_PickableKrepysh_LessSelfDamage_Recipe.. | |
| Krepysh RocketLanding/Крепыш Посадка ракет | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/Upgrades/Krepysh/BP_PickableKrepysh_RocketLanding_Recipe.. | |
| **KS-23 Upgrades/Улучшения КС-23** |                                                               |                             |
| KS-23 Barrel AO/КС-23 Ствол AO | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/Upgrades/KS23/BP_Pickable_KS23_BarrelAO_Recipe.. | |
| KS-23 Barrel AR/КС-23 Ствол AR | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/Upgrades/KS23/BP_Pickable_KS23_BarrelAR_Recipe.. | |
| KS-23 Cassette/КС-23 Кассета | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/Upgrades/KS23/BP_Pickable_KS23_Casette_Recipe.. | |
| KS-23 Fire Rate/КС-23 Скорострельность | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/Upgrades/KS23/BP_Pickable_KS23_FireRate_Recipe.. | |
| KS-23 Scope Capacity/КС-23 Прицел ёмкость | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/Upgrades/KS23/BP_Pickable_KS23_Scope_Capacity_Recipe.. | |
| KS-23 Scope RedDot/КС-23 Коллиматор | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/Upgrades/KS23/BP_Pickable_KS23_Scope_RedDot_Recipe.. | |
| KS-23 Scope Thermal/КС-23 Тепловизор | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/Upgrades/KS23/BP_Pickable_KS23_Scope_Thermal_Recipe.. | |
| **Lisa Upgrades/Улучшения Лисы** |                                                                 |                             |
| Lisa Blade/Лиса Лезвие       | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/Upgrades/Lisa/BP_Pickable_Lisa_Blade_Recipe.. |  |
| Lisa Cassette/Лиса Кассета   | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/Upgrades/Lisa/BP_Pickable_Lisa_Casette_Recipe.. | |
| Lisa Handle/Лиса Рукоятка    | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/Upgrades/Lisa/BP_Pickable_Lisa_Handle_Recipe.. | |
| **Pashtet Upgrades/Улучшения Паштета** |                                                          |                             |
| Pashtet Blade/Паштет Лезвие  | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/Upgrades/Pashtet/BP_Pickable_Pashtet_Blade_Recipe.. | |
| Pashtet Cassette/Паштет Кассета | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/Upgrades/Pashtet/BP_Pickable_Pashtet_Casset_Recipe.. | |
| Pashtet FlyingBlades/Паштет Летающие лезвия | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/Upgrades/Pashtet/BP_Pickable_Pashtet_FlyingBlades_Recipe.. | |
| Pashtet Handle/Паштет Рукоятка | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/Upgrades/Pashtet/BP_Pickable_Pashtet_Handle_Recipe.. | |
| **PM Upgrades/Улучшения ПМ** |                                                                     |                             |
| PM Barrel AO/ПМ Ствол AO     | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/Upgrades/PM/BP_Pickable_PM_BarrelAO_Recipe.. |   |
| PM Barrel AR/ПМ Ствол AR     | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/Upgrades/PM/BP_Pickable_PM_BarrelAR_Recipe.. |   |
| PM Cassette/ПМ Кассета       | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/Upgrades/PM/BP_Pickable_PM_Cassette_Recipe.. |   |
| PM Revolver/ПМ Револьвер     | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/Upgrades/PM/BP_Pickable_PM_Revolver_Recipe.. |   |
| PM Scope Capacity/ПМ Прицел ёмкость | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/Upgrades/PM/BP_Pickable_PM_Scope_Capacity_Recipe.. | |
| PM Scope RedDot/ПМ Коллиматор | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/Upgrades/PM/BP_Pickable_PM_Scope_RedDot_Recipe.. | |
| PM Scope Thermal/ПМ Тепловизор | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/Upgrades/PM/BP_Pickable_PM_Scope_Thermal_Recipe.. | |
| **Shved Upgrades/Улучшения Шведа** |                                                               |                             |
| Shved Blade/Швед Лезвие      | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/Upgrades/Shved/BP_Pickable_Shved_Blade_Recipe.. | |
| Shved Cassette/Швед Кассета  | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/Upgrades/Shved/BP_Pickable_Shved_Cassette_Recipe.. | |
| Shved Handle/Швед Рукоятка   | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/Upgrades/Shved/BP_Pickable_Shved_Handle_Recipe.. | |
| Shved PowerAttack/Швед Мощная атака | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/Upgrades/Shved/BP_Pickable_Shved_PowerAttack_Recipe.. | |
| **Snejok Upgrades/Улучшения Снежка** |                                                             |                             |
| Snejok Cassette/Снежок Кассета | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/Upgrades/Snejok/BP_Pickable_Snejok_Cassette_Recipe.. | |
| Snejok Handle/Снежок Рукоятка | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/Upgrades/Snejok/BP_Pickable_Snejok_Handle_Recipe.. | |
| Snejok Head/Снежок Голова    | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/Upgrades/Snejok/BP_Pickable_Snejok_Head_Recipe.. | |
| Snejok RamAttack/Снежок Таранная атака | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/Upgrades/Snejok/BP_Pickable_Snejok_RamAttack_Recipe.. | |
| **Zvezdochka Upgrades/Улучшения Звёздочки** |                                                     |                             |
| Zvezdochka Cassette/Звёздочка Кассета | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/Upgrades/Zvezdochka/BP_Pickable_Zvezdochka_Cassette_Recipe.. | |
| Zvezdochka ExtraSaw/Звёздочка Доп. пила | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/Upgrades/Zvezdochka/BP_Pickable_Zvezdochka_ExtraSaw_Recipe.. | |
| Zvezdochka Handle/Звёздочка Рукоятка | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/Upgrades/Zvezdochka/BP_Pickable_Zvezdochka_Handle_Recipe.. | |
| Zvezdochka SawsAttack/Звёздочка Атака пилами | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/Upgrades/Zvezdochka/BP_Pickable_Zvezdochka_SawsAttack_Recipe.. | |
| **Lapta Upgrades/Улучшения Лапты** |                                                                 |                             |
| Lapta Blade/Лапта Лезвие     | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/Upgrades/Lapta/BP_Pickable_Lapta_Blade_Recipe.. |  |
| Lapta Cassette/Лапта Кассета | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/Upgrades/Lapta/BP_Pickable_Lapta_Casette_Recipe.. | |
| Lapta Handle/Лапта Рукоятка  | AtomicHeart/Content/Core/Objects/Items/RecipesTubus/Upgrades/Lapta/BP_Pickable_Lapta_Handle_Recipe.. | |
| **Klusha Upgrades/Улучшения Клуши** |                                                               | DLC #1                      |
| Klusha Blade/Клуша Лезвие   | AtomicHeart/Content/DLC/Core/Weapons/Melee/Klusha/Upgrades/BP_Pickable_Klusha_UpgradeBlades_Recipe.. | |
| Klusha Cassette/Клуша Кассета | AtomicHeart/Content/DLC/Core/Weapons/Melee/Klusha/Upgrades/BP_Pickable_Klusha_UpgradeCasette_Recipe.. | |
| Klusha Handle/Клуша Рукоятка | AtomicHeart/Content/DLC/Core/Weapons/Melee/Klusha/Upgrades/BP_Pickable_Klusha_UpgradeHandle_Recipe.. | |
| **Thunderclap Upgrades/Улучшения Громовержца** |                                                    | DLC #3                      |
| Thunderclap Handle/Громовержец Рукоятка | AtomicHeart/Content/DLC3/Core/Weapons/Melee/Gromoverzec/Upgrades_Grom/BP_Pickable_Gromoverzhec_UpgradeHandle_Recipe.. | |
| Thunderclap Head/Громовержец Голова | AtomicHeart/Content/DLC3/Core/Weapons/Melee/Gromoverzec/Upgrades_Grom/BP_Pickable_Gromoverzhec_UpgradeHead_Recipe.. | |
| **Plasma Gun Upgrades/Улучшения Плазмагана** |                                                    | DLC #1                      |
| Plasma Gun Barrel/Плазмаган Ствол | AtomicHeart/Content/DLC/Core/Weapons/Range/Plasmagun/Upgrades/BP_Pickable_Plasmagun_UpgradedBarrel_Recipe.. | |
| Plasma Gun Magnets/Плазмаган Магниты | AtomicHeart/Content/DLC/Core/Weapons/Range/Plasmagun/Upgrades/BP_Pickable_Plasmagun_UpgradeIncreaseWaveSpeed_Recipe.. | |
| **Kuzmich Upgrades/Улучшения Кузьмича** |                                                         | DLC #3                      |
| Kuzmich Barrel Plane/Кузьмич Ствол плоский | AtomicHeart/Content/DLC3/Core/Weapons/Range/Kuzmich/Upgrades_Kuzm/BP_Pickable_Kuzmich_UpgradedPlaneBarrel_Recipe.. | |
| Kuzmich Barrel Plug/Кузьмич Ствол пробка | AtomicHeart/Content/DLC3/Core/Weapons/Range/Kuzmich/Upgrades_Kuzm/BP_Pickable_Kuzmich_UpgradedSlugBarrel_Recipe.. | |
| Kuzmich Magazine/Кузьмич Магазин | AtomicHeart/Content/DLC3/Core/Weapons/Range/Kuzmich/Upgrades_Kuzm/BP_Pickable_Kuzmich_UpgradeMagazine_Recipe.. | |
| Kuzmich Stock/Кузьмич Приклад | AtomicHeart/Content/DLC3/Core/Weapons/Range/Kuzmich/Upgrades_Kuzm/BP_Pickable_Kuzmich_UpgradeStock_Recipe.. | |
| **Interactive Objects/Интерактивные объекты** |                                                   |                             |
| Craft Machine/Станок крафта  | AtomicHeart/Content/Core/Objects/Interactive/CraftMachine/BP_Base_CraftMachine.. |              |
| Craft Machine Camera/Станок крафта с камерой | AtomicHeart/Content/Core/Objects/Interactive/CraftMachine/BP_CraftMachine_AdditionalCamera.. | |
| Loot Box/Ящик с лутом        | AtomicHeart/Content/Core/Objects/LootCrates/LootBox_04/LB_DefaultLootBox_04.. |                 |
| Medic Box/Аптечный ящик      | AtomicHeart/Content/Core/Objects/Items/Props/BP_MedicSmallBox_Open4.. |                         |
| **Quest Objects/Квестовые предметы** |                                                             |                             |
| Coin/Монета                  | AtomicHeart/Content/Core/Objects/Items/QuestObjects/BP_Pickable_Coin.. |                        |
| Kuzmich/Кузьмич              | AtomicHeart/Content/Core/Objects/Items/BP_Pickupable_Kuzmich..     |                            |
| **Canisters for Lunar Lock/Колбы для Луны** |                                                                |                             |
| Canister (circle)/Колба (круг) | AtomicHeart/Content/Core/Objects/Interactive/Puzzles/BP_Pickable_Puzzle_Piece.. |            |
| Canister (Square)/Колба (квадрат | AtomicHeart/Content/Core/Objects/Interactive/Puzzles/BP_Pickable_Puzzle_Piece_Square.. |            |
| Canister (Triangle)/Колба (треугольник) | AtomicHeart/Content/Core/Objects/Interactive/Puzzles/BP_Pickable_Puzzle_Piece_Triangle.. |            |
| **DLC1 Enemies/DLC1 Враги**  |                                                                   |                             |
| Busa Boss/Буса Босс          | AtomicHeart/Content/DLC/Core/AI/Characters/Busa/Boss/BP_Busa_Boss_Character.. |                 |
| Busa Blue/Буса синяя         | AtomicHeart/Content/DLC/Core/AI/Characters/Busa/BP_Busa_Single_Character_Colored_Blue.. |       |
| Busa Centaur/Буса Кентавр    | AtomicHeart/Content/DLC/Core/AI/Characters/Busa/BP_Busa_Centaur_Character.. |                   |
| Goose/Гусь                   | AtomicHeart/Content/DLC/Core/AI/Characters/GOOSE/BP_Goose_Character.. |                         |
| Maniken/Манекен              | AtomicHeart/Content/DLC/Core/AI/Characters/Maniken/BP_ManikenCharacter.. |                       |
| **DLC2 Enemies/DLC2 Враги**  |                                                                   |                             |
| Raf Limbo/Раф Лимбо          | AtomicHeart/Content/DLC2/Development/NPC/BP_RafCharacter_Limbo..   |                            |
| Raf Limbo BoxSpawn/Раф Лимбо со спавном | AtomicHeart/Content/DLC2/Development/NPC/BP_RafCharacter_Limbo_BoxSpawn.. |          |
| Shakal Limbo/Шакал Лимбо     | AtomicHeart/Content/DLC2/Development/NPC/BP_Shakal_Limbo..         |                            |
| Vov Kamikadze/ВОВ Камикадзе  | AtomicHeart/Content/DLC2/Development/NPC/BP_VovCharacter_Kamikadze.. |                          |
| Vov Limbo Parent/ВОВ Лимбо   | AtomicHeart/Content/DLC2/Development/NPC/BP_VovCharacter_LimboParent.. |                        |
| Vov Pryanik Fast/ВОВ Пряник быстрый | AtomicHeart/Content/DLC2/Development/NPC/BP_VovCharacter_PryanikFast.. |                |
| Vov Pryanik Baloon/ВОВ Пряник с шаром | AtomicHeart/Content/DLC2/Development/NPC/BP_VovCharacter_PryanikFast_Baloon.. |         |
| Vov Pryanik Slow/ВОВ Пряник медленный | AtomicHeart/Content/DLC2/Development/NPC/BP_VovCharacter_PryanikSlow.. |               |
| Vov Translocator/ВОВ Транслокатор | AtomicHeart/Content/DLC2/Development/NPC/BP_VovCharacter_Translocator.. |                |
| Goose Limbo/Гусь Лимбо       | AtomicHeart/Content/DLC2/Development/NPC/Gooses/BP_Goose_Character_Limbo.. |                    |
| **DLC3 Collectibles/DLC3 Коллекционные предметы** |                                                   | DLC #3                      |
| Dolphin Football/Дельфин футболист | AtomicHeart/Content/DLC3/Development/Blueprints/Blueprint_Objects/PickableMaskot/BP_Pickble_Dolphin_Mascot_Dolphin_FootBall.. | |
| Dolphin Police/Дельфин полицейский | AtomicHeart/Content/DLC3/Development/Blueprints/Blueprint_Objects/PickableMaskot/BP_Pickble_Dolphin_Mascot_Dolphin_Police.. | |
| Dolphin Doctor/Дельфин доктор | AtomicHeart/Content/DLC3/Development/Blueprints/Blueprint_Objects/PickableMaskot/BP_Pickupable_Dolphin_Doctor.. | |
| Dolphin Panama/Дельфин в панаме | AtomicHeart/Content/DLC3/Development/Blueprints/Blueprint_Objects/PickableMaskot/BP_Pickble_Dolphin_Mascot_Dolphin_Panama.. | |
| Dolphin Common/Дельфин обычный | AtomicHeart/Content/DLC3/Development/Blueprints/Blueprint_Objects/PickableMaskot/BP_Pickble_Dolphin_Mascot.. | |
| **Environmental Objects/Объекты окружения** |                                                        |                             |
| Power Plant Child/Электростанция | /Game/Core/AI/Characters/PowerPlant/BP_PowerPlant_Child..   | Environmental               |
