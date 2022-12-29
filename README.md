# GBA_stuff
<h1> tools that i am using: </h1>

- [HexManiacAdvance](https://github.com/haven1433/HexManiacAdvance)
- [mGBA - GBA emulator](https://github.com/mgba-emu/mgba)
- [Advanced Map Editor](http://getam.no-ip.info/?ver=1.95)

<h2> Known issues with HMA: </h2>
Speaking with the developer at the moment only "BPEE" is supported (pokemon emerald english version).

But we can [edit](https://github.com/haven1433/HexManiacAdvance/wiki/TOML-and-You:-How-Metadata-works) the .toml file that is created (named "gbaromname.toml") when the tool is started.<br>
For the correct addresses we can refer to
<details>
    <summary>
        [this](https://github.com/Gamer2020/PokemonGameEditor/blob/master/roms.ini) list of values
    </summary>
    
    ```
    | Name                                  | BPEE                                   | BPEI                        | toml_Ref |
    | ------------------------------------- | -------------------------------------- | --------------------------- | --------- |
    |  ROMName                              | Pokemon Emerald (English)              | Pokemon Smeraldo (Italiano) |
    |  ItemData                             | 5839A0                                 | 58000C                      | ✔(data.items.stats)          |
    |  AttackNames                          | 31977C                                 | 319140                      | ✔(data.pokemon.moves.names)          |
    |  TMData                               | 616040                                 | 612BDC                      | ✔(data.pokemon.moves.tms)          |
    |  TotalTMsPlusHMs                      | 58                                     | 58                          |           |
    |  TotalTMs                             | 50                                     | 50                          |           |
    |  ItemIMGData                          | 614410                                 | 610FAC                      | ✔(graphics.items.sprites)          |
    |  NumberOfItems                        | 377                                    | 377                         |           |
    |  NumberOfAttacks                      | 354                                    | 354                         |           |
    |  MoveTutorAttacks                     | 61500C                                 | 611BA8                      | ✔(data.pokemon.moves.tutors)          |
    |  NumberOfMoveTutorAttacks             | 32                                     | 32                          |           |
    |  PokemonNames                         | 3185C8                                 | 317F8C                      | ✔(data.pokemon.names)          |
    |  NumberOfPokemon                      | 412                                    | 412                         |           |
    |  NationalDexTable                     | 31DC82                                 | 31D682                      | ✔(data.pokedex.national)          |
    |  SecondDexTable                       | 31D94C                                 | 31D34C                      | ✔(data.pokedex.regional)         |
    |  HoenntoNationalDex                   | 31DFB8                                 | 31D9B8                      | ✔(data.pokedex.hoennToNational)          |
    |  PokedexData                          | 56B5B0                                 | 568C80                      | ✔(data.pokedex.stats)          |
    |  NumberOfDexEntries                   | 387                                    | 387                         |           |
    |  NumberOfRegionDex                    | 202                                    | 202                         |           |
    |  PokemonData                          | 3203CC                                 | 31FDCC                      | ✔(data.pokemon.stats)         |
    |  AbilityNames                         | 31B6DB                                 | 31B0DB                      | ✔ (data.abilities.name)          |
    |  NumberOfAbilities                    | 78                                     | 78                          |           |
    |  Pointer2PointersToMapBanks           | 84AA4                                  | 84AB8                       |           |
    |  OriginalBankPointer0                 | 485D60                                 |                             |           |
    |  OriginalBankPointer1                 | 485E44                                 |                             |           |
    |  OriginalBankPointer2                 | 485E58                                 |                             |           |
    |  OriginalBankPointer3                 | 485E6C                                 |                             |           |
    |  OriginalBankPointer4                 | 485E84                                 |                             |           |
    |  OriginalBankPointer5                 | 485EA0                                 |                             |           |
    |  OriginalBankPointer6                 | 485EC0                                 |                             |           |
    |  OriginalBankPointer7                 | 485EE4                                 |                             |           |
    |  OriginalBankPointer8                 | 485F00                                 |                             |           |
    |  OriginalBankPointer9                 | 485F1C                                 |                             |           |
    |  OriginalBankPointer10                | 485F54                                 |                             |           |
    |  OriginalBankPointer11                | 485F74                                 |                             |           |
    |  OriginalBankPointer12                | 485FB8                                 |                             |           |
    |  OriginalBankPointer13                | 485FE0                                 |                             |           |
    |  OriginalBankPointer14                | 48603C                                 |                             |           |
    |  OriginalBankPointer15                | 486070                                 |                             |           |
    |  OriginalBankPointer16                | 4860AC                                 |                             |           |
    |  OriginalBankPointer17                | 4860E8                                 |                             |           |
    |  OriginalBankPointer18                | 4860F0                                 |                             |           |
    |  OriginalBankPointer19                | 4860F8                                 |                             |           |
    |  OriginalBankPointer20                | 486100                                 |                             |           |
    |  OriginalBankPointer21                | 48610C                                 |                             |           |
    |  OriginalBankPointer22                | 486110                                 |                             |           |
    |  OriginalBankPointer23                | 486114                                 |                             |           |
    |  OriginalBankPointer24                | 486118                                 |                             |           |
    |  OriginalBankPointer25                | 4862C8                                 |                             |           |
    |  OriginalBankPointer26                | 4863BC                                 |                             |           |
    |  OriginalBankPointer27                | 486520                                 |                             |           |
    |  OriginalBankPointer28                | 486528                                 |                             |           |
    |  OriginalBankPointer29                | 48652C                                 |                             |           |
    |  OriginalBankPointer30                | 486560                                 |                             |           |
    |  OriginalBankPointer31                | 486564                                 |                             |           |
    |  OriginalBankPointer32                | 486568                                 |                             |           |
    |  OriginalBankPointer33                | 486574                                 |                             |           |
    |  NumberOfMapsInBank0                  | 56                                     |                             |           |
    |  NumberOfMapsInBank1                  | 4                                      |                             |           |
    |  NumberOfMapsInBank2                  | 4                                      |                             |           |
    |  NumberOfMapsInBank3                  | 5                                      |                             |           |
    |  NumberOfMapsInBank4                  | 6                                      |                             |           |
    |  NumberOfMapsInBank5                  | 7                                      |                             |           |
    |  NumberOfMapsInBank6                  | 8                                      |                             |           |
    |  NumberOfMapsInBank7                  | 6                                      |                             |           |
    |  NumberOfMapsInBank8                  | 6                                      |                             |           |
    |  NumberOfMapsInBank9                  | 13                                     |                             |           |
    |  NumberOfMapsInBank10                 | 7                                      |                             |           |
    |  NumberOfMapsInBank11                 | 16                                     |                             |           |
    |  NumberOfMapsInBank12                 | 9                                      |                             |           |
    |  NumberOfMapsInBank13                 | 22                                     |                             |           |
    |  NumberOfMapsInBank14                 | 12                                     |                             |           |
    |  NumberOfMapsInBank15                 | 14                                     |                             |           |
    |  NumberOfMapsInBank16                 | 14                                     |                             |           |
    |  NumberOfMapsInBank17                 | 1                                      |                             |           |
    |  NumberOfMapsInBank18                 | 1                                      |                             |           |
    |  NumberOfMapsInBank19                 | 1                                      |                             |           |
    |  NumberOfMapsInBank20                 | 2                                      |                             |           |
    |  NumberOfMapsInBank21                 | 0                                      |                             |           |
    |  NumberOfMapsInBank22                 | 0                                      |                             |           |
    |  NumberOfMapsInBank23                 | 0                                      |                             |           |
    |  NumberOfMapsInBank24                 | 107                                    |                             |           |
    |  NumberOfMapsInBank25                 | 60                                     |                             |           |
    |  NumberOfMapsInBank26                 | 88                                     |                             |           |
    |  NumberOfMapsInBank27                 | 1                                      |                             |           |
    |  NumberOfMapsInBank28                 | 0                                      |                             |           |
    |  NumberOfMapsInBank29                 | 12                                     |                             |           |
    |  NumberOfMapsInBank30                 | 0                                      |                             |           |
    |  NumberOfMapsInBank31                 | 0                                      |                             |           |
    |  NumberOfMapsInBank32                 | 2                                      |                             |           |
    |  NumberOfMapsInBank33                 | 0                                      |                             |           |
    |  MapLabelData                         | 5A1480                                 | 59DEEC                      |           |
    |  NumberOfMapLabels                    | 213                                    | 213                         |           |
    |  PokemonFrontSprites                  | 301418                                 | 300DDC                      |           |
    |  PokemonBackSprites                   | 3028B8                                 | 30227C                      |           |
    |  PokemonNormalPal                     | 303678                                 | 30303C                      |           |
    |  PokemonShinyPal                      | 304438                                 | 303DFC                      |           |
    |  PokemonAnimations                    | 30A18C                                 | 309B50                      |           |
    |  FrontAnimationTable                  | 3299EC                                 | 3293EC                      |           |
    |  BackAnimTable                        | 60A8C8                                 | 607464                      |           |
    |  AnimDelayTable                       | 329B87                                 | 329587                      |           |
    |  IconPointerTable                     | 57BCA8                                 | 57838C                      |           |
    |  IconPalTable                         | 57C388                                 | 578A6C                      |           |
    |  CryTable                             | 69DCF4                                 | 69A380                      |           |
    |  CryTable2                            | 69EF24                                 | 69B538                      |           |
    |  CryConversionTable                   | 31F61C                                 | 31F01C                      |           |
    |  FootPrintTable                       | 56E694                                 | 56BD64                      |           |
    |  PokemonAttackTable                   | 32937C                                 | 328D7C                      |           |
    |  PokemonEvolutions                    | 32531C                                 | 324D1C                      |           |
    |  TMHMCompatibility                    | 31E898                                 | 31E298                      |           |
    |  TMHMLenPerPoke                       | 8                                      | 8                           |           |
    |  MoveTutorCompatibility               | 615048                                 | 611BE4                      |           |
    |  EnemyYTable                          | 300D38                                 | 3006FC                      |           |
    |  PlayerYTable                         | 3021D8                                 | 301B9C                      |           |
    |  EnemyAltitudeTable                   | 305DCC                                 | 305790                      |           |
    |  AttackData                           | 31C898                                 | 31C298                      |           |
    |  ContestMoveData                      | 58C2B4                                 | 5888F4                      |           |
    |  ContestMoveEffectData                | 58CDCC                                 | 58940C                      |           |
    |  AttackDescriptionTable               | 61C524                                 | 619038                      |           |
    |  AbilityDescriptionTable              | 31BAD4                                 | 31B4D4                      |           |
    |  StarterPokemon                       | 5B1DF8                                 | 5AE994                      | ✔ (scripts.newgame.starters.pokemon)          |
    |  StarterPokemonLevel                  | B1178                                  | B118C                       |           |
    |  StarterEncounterPokemon              | 32706                                  | 3270A                       |           |
    |  StarterEncounterPokemonLevel         | 32714                                  | 32718                       |           |
    |  AttackAnimationTable                 | 2C8D6C                                 | 2C9CF8                      |           |
    |  BattleFrontierTrainers               | 5D5ACC                                 | 5D2614                      |           |
    |  SlateportBattleTentTrainers          | 5DDA14                                 | 5DA55C                      |           |
    |  VerdanturfBattleTentTrainers         | 5DE610                                 | 5DB158                      |           |
    |  FallarborBattleTentTrainers          | 5DF084                                 | 5dbbcc                      |           |
    |  NumberOfBattleFrontierTrainers       | 300                                    | 300                         |           |
    |  NumberOfSlateportBattleTentTrainers  | 30                                     | 30                          |           |
    |  NumberOfVerdanturfBattleTentTrainers | 30                                     | 30                          |           |
    |  NumberOfFallarborBattleTentTrainers  | 30                                     | 30                          |           |
    |  BattleFrontierPokemon                | 5D97BC                                 | 5D6304                      |           |
    |  SlateportBattleTentPokemon           | 5DE02C                                 | 5DAB74                      |           |
    |  VerdanturfBattleTentPokemon          | 5DEC28                                 | 5DB770                      |           |
    |  FallarborBattleTentPokemon           | 5DF69C                                 | 5DC1E4                      |           |
    |  NumberOfBattleFrontierPokemon        | 882                                    | 882                         |           |
    |  NumberOfSlateportBattleTentPokemon   | 70                                     | 70                          |           |
    |  NumberOfVerdanturfBattleTentPokemon  | 45                                     | 45                          |           |
    |  NumberOfFallarborBattleTentPokemon   | 45                                     | 45                          |           |
    |  BattleFrontierHeldItems              | 5CECB0                                 | 5CB7F8                      |           |
    |  BattleFrontierBanList                | 611C9A                                 | 60E836                      |           |
    |  NumberOfBattlefrontierHeldItems      | 62                                     | 62                          |           |
    |  NumberOfTilesInTilset3DF71C          | 8F                                     |                             |           |
    |  NumberOfTilesInTilset3DF734          | 15D                                    |                             |           |
    |  NumberOfTilesInTilset3DF74C          | 17A                                    |                             |           |
    |  NumberOfTilesInTilset3DF764          | 197                                    |                             |           |
    |  NumberOfTilesInTilset3DF77C          | 1FF                                    |                             |           |
    |  NumberOfTilesInTilset3DF794          | 1B8                                    |                             |           |
    |  NumberOfTilesInTilset3DF7AC          | 16F                                    |                             |           |
    |  NumberOfTilesInTilset3DF7C4          | 117                                    |                             |           |
    |  NumberOfTilesInTilset3DF7DC          | 15F                                    |                             |           |
    |  NumberOfTilesInTilset3DF7F4          | 1C7                                    |                             |           |
    |  NumberOfTilesInTilset3DF80C          | A7                                     |                             |           |
    |  NumberOfTilesInTilset3DF824          | CA                                     |                             |           |
    |  NumberOfTilesInTilset3DF83C          | FE                                     |                             |           |
    |  NumberOfTilesInTilset3DF86C          | 1FF                                    |                             |           |
    |  NumberOfTilesInTilset3DF884          | C6                                     |                             |           |
    |  NumberOfTilesInTilset3DF89C          | 120                                    |                             |           |
    |  NumberOfTilesInTilset3DF8B4          | E7                                     |                             |           |
    |  NumberOfTilesInTilset3DF8CC          | 19D                                    |                             |           |
    |  NumberOfTilesInTilset3DF8E4          | 39                                     |                             |           |
    |  NumberOfTilesInTilset3DF8FC          | 67                                     |                             |           |
    |  NumberOfTilesInTilset3DF914          | 65                                     |                             |           |
    |  NumberOfTilesInTilset3DF92C          | 9E                                     |                             |           |
    |  NumberOfTilesInTilset3DF944          | 79                                     |                             |           |
    |  NumberOfTilesInTilset3DF95C          | FF                                     |                             |           |
    |  NumberOfTilesInTilset3DF974          | 37                                     |                             |           |
    |  NumberOfTilesInTilset3DF98C          | 47                                     |                             |           |
    |  NumberOfTilesInTilset3DF9A4          | 43                                     |                             |           |
    |  NumberOfTilesInTilset3DF9BC          | 1FF                                    |                             |           |
    |  NumberOfTilesInTilset3DF9D4          | F7                                     |                             |           |
    |  NumberOfTilesInTilset3DF9EC          | 52                                     |                             |           |
    |  NumberOfTilesInTilset3DFA04          | 143                                    |                             |           |
    |  NumberOfTilesInTilset3DFA1C          | 143                                    |                             |           |
    |  NumberOfTilesInTilset3DFA34          | 143                                    |                             |           |
    |  NumberOfTilesInTilset3DFA4C          | 143                                    |                             |           |
    |  NumberOfTilesInTilset3DFA64          | 26                                     |                             |           |
    |  NumberOfTilesInTilset3DFA7C          | 3A                                     |                             |           |
    |  NumberOfTilesInTilset3DFA94          | 25                                     |                             |           |
    |  NumberOfTilesInTilset3DFAAC          | 8F                                     |                             |           |
    |  NumberOfTilesInTilset3DFAC4          | E8                                     |                             |           |
    |  NumberOfTilesInTilset3DFADC          | 8E                                     |                             |           |
    |  NumberOfTilesInTilset3DFAF4          | C3                                     |                             |           |
    |  NumberOfTilesInTilset3DFB0C          | 9D                                     |                             |           |
    |  NumberOfTilesInTilset3DFB24          | EB                                     |                             |           |
    |  NumberOfTilesInTilset3DFB3C          | DF                                     |                             |           |
    |  NumberOfTilesInTilset3DFB54          | 79                                     |                             |           |
    |  NumberOfTilesInTilset3DFB6C          | 1FF                                    |                             |           |
    |  NumberOfTilesInTilset3DFB84          | 5F                                     |                             |           |
    |  NumberOfTilesInTilset3DFB9C          | 52                                     |                             |           |
    |  NumberOfTilesInTilset3DFBB4          | 44                                     |                             |           |
    |  NumberOfTilesInTilset3DFBCC          | 95                                     |                             |           |
    |  NumberOfTilesInTilset3DFBE4          | 3C                                     |                             |           |
    |  NumberOfTilesInTilset3DFBFC          | BC                                     |                             |           |
    |  NumberOfTilesInTilset3DFC14          | 47                                     |                             |           |
    |  NumberOfTilesInTilset3DFC2C          | 74                                     |                             |           |
    |  NumberOfTilesInTilset3DFC44          | FB                                     |                             |           |
    |  NumberOfTilesInTilset3DFC7C          | 14B                                    |                             |           |
    |  NumberOfTilesInTilset3DFC94          | 1FF                                    |                             |           |
    |  NumberOfTilesInTilset3DFCAC          | 19E                                    |                             |           |
    |  NumberOfTilesInTilset3DFCC4          | 1AA                                    |                             |           |
    |  NumberOfTilesInTilset3DFCDC          | 15F                                    |                             |           |
    |  NumberOfTilesInTilset3DFCF4          | 15B                                    |                             |           |
    |  NumberOfTilesInTilset3DFD0C          | B0                                     |                             |           |
    |  NumberOfTilesInTilset3DFD24          | DC                                     |                             |           |
    |  NumberOfTilesInTilset3DFD3C          | 19D                                    |                             |           |
    |  NumberOfTilesInTilset3DFD54          | 34                                     |                             |           |
    |  NumberOfTilesInTilset3DFD6C          | 42                                     |                             |           |
    |  NumberOfTilesInTilset3DFD84          | 1CF                                    |                             |           |
    |  NumberOfTilesInTilset3DFD9C          | 1C2                                    |                             |           |
    |  NumberOfTilesInTilset3DFDB4          | 5D                                     |                             |           |
    |  NumberOfTilesInTilset3DFDCC          | 10C                                    |                             |           |
    |  NumberOfTilesInTilset3DFDE4          | 42                                     |                             |           |
    |  NumberOfTilesInTilset3DFDFC          | 30                                     |                             |           |
    |  IconPals                             | DDE1F8                                 | DDE1D8                      |           |
    |  ShadowFronts                         | 1000000                                |                             |           |
    |  ShadowPals                           | 1002660                                |                             |           |
    |  ShadowBacks                          | 1007320                                |                             |           |
    |  JamboLearnableMovesTerm              | 0000FF                                 |                             |           |
    |  StartSearchingForSpaceOffset         | E3CF64                                 | E3D0B0                      |           |
    |  FreeSpaceSearchInterval              | 100                                    | 100                         |           |
    |  NumberOfEvolutionsPerPokemon         | 5                                      | 5                           |           |
    |  NumberOfEvolutionTypes               | 255                                    | 15                          |           |
    |  EvolutionName0                       | None                                   | None                        |           |
    |  EvolutionName1                       | Happiness                              | Felicita                    |           |
    |  EvolutionName2                       | Happiness (Day)                        | Felicita (Giorno)           |           |
    |  EvolutionName3                       | Happiness (Night)                      | Felicita (Notte)            |           |
    |  EvolutionName4                       | Level                                  | Livello                     |           |
    |  EvolutionName5                       | Trade                                  | Scambio                     |           |
    |  EvolutionName6                       | Trade w/ Item                          | Scambio con Ogg.            |           |
    |  EvolutionName7                       | Item                                   | Oggetto                     |           |
    |  EvolutionName8                       | Atk > Def                              | Atk > Def                   |           |
    |  EvolutionName9                       | Atk                                    | Atk                         |           |
    |  EvolutionName10                      | Atk < Def                              | Atk < Def                   |           |
    |  EvolutionName11                      | High Personality                       | High Personality            |           |
    |  EvolutionName12                      | Low Personality                        | Low Personality             |           |
    |  EvolutionName13                      | Allow Pokemon Creation                 | Allow Pokemon Creation      |           |
    |  EvolutionName14                      | Create Extra Pokemon                   | Create Extra Pokemon        |           |
    |  EvolutionName15                      | Max Beauty                             | Bellezza Massima            |           |
    |  Evolution0Param                      | none                                   | none                        |           |
    |  Evolution1Param                      | evolvesbutnoparms                      | evolvesbutnoparms           |           |
    |  Evolution2Param                      | evolvesbutnoparms                      | evolvesbutnoparms           |           |
    |  Evolution3Param                      | evolvesbutnoparms                      | evolvesbutnoparms           |           |
    |  Evolution4Param                      | level                                  | level                       |           |
    |  Evolution5Param                      | evolvesbutnoparms                      | evolvesbutnoparms           |           |
    |  Evolution6Param                      | item                                   | item                        |           |
    |  Evolution7Param                      | item                                   | item                        |           |
    |  Evolution8Param                      | level                                  | level                       |           |
    |  Evolution9Param                      | level                                  | level                       |           |
    |  Evolution10Param                     | level                                  | level                       |           |
    |  Evolution11Param                     | level                                  | level                       |           |
    |  Evolution12Param                     | level                                  | level                       |           |
    |  Evolution13Param                     | evolvesbutnoparms                      | evolvesbutnoparms           |           |
    |  Evolution14Param                     | level                                  | level                       |           |
    |  Evolution15Param                     | evolvesbasedonvalue                    | evolvesbasedonvalue         |           |
    |  EvolutionName16                      | Knows Move                             |                             |           |
    |  Evolution16Param                     | attack                                 |                             |           |
    |  EvolutionName17                      | In certain map                         |                             |           |
    |  Evolution17Param                     | mapname                                |                             |           |
    |  EvolutionName18                      | Level-up at day                        |                             |           |
    |  Evolution18Param                     | level                                  |                             |           |
    |  EvolutionName19                      | Level-up at night                      |                             |           |
    |  Evolution19Param                     | level                                  |                             |           |
    |  EvolutionName20                      | Holding item at day                    |                             |           |
    |  Evolution20Param                     | item                                   |                             |           |
    |  EvolutionName21                      | Holding item at night                  |                             |           |
    |  Evolution21Param                     | item                                   |                             |           |
    |  EvolutionName22                      | Level-up if male                       |                             |           |
    |  Evolution22Param                     | level                                  |                             |           |
    |  EvolutionName23                      | Level-up if female                     |                             |           |
    |  Evolution23Param                     | level                                  |                             |           |
    |  EvolutionName24                      | Level-up if raining                    |                             |           |
    |  Evolution24Param                     | level                                  |                             |           |
    |  EvolutionName25                      | Specific Pokemon in party              |                             |           |
    |  Evolution25Param                     | species                                |                             |           |
    |  EvolutionName26                      | Level-up if pokemon with type in party |                             |           |
    |  Evolution26Param                     | bankandmap                             |                             |           |
    |  EvolutionName27                      | Using item if male                     |                             |           |
    |  Evolution27Param                     | item                                   |                             |           |
    |  EvolutionName28                      | Using item if female                   |                             |           |
    |  Evolution28Param                     | item                                   |                             |           |
    |  EvolutionName252                     | Wish Mega Evolution                    |                             |           |
    |  Evolution252Param                    | attack                                 |                             |           |
    |  EvolutionName251                     | Mega Evolution                         |                             |           |
    |  Evolution251Param                    | item                                   |                             |           |
    |  EvolutionName255                     | Revert Megas                           |                             |           |
    |  Evolution255Param                    | evolvesbutnoparms                      |                             |           |
    |  EvolutionName253                     | Primal Reversion                       |                             |           |
    |  Evolution253Param                    | evolvesbasedonvalue                    |                             |           |
    |  EggMoveTable                         | 32ADD8                                 | 32A7D8                      |           |
    |  EggMoveTableLimiter                  | 70464                                  | 70464                       |           |
    |  TrainerTable                         | 310030                                 | 30FA1C                      | ✔  (data.trainers.stats)          |
    |  NumberOfTrainers                     | 854                                    | 854                         |           |
    |  TrainerClasses                       | 30FCD4                                 | 30F698                      |           |
    |  NumberOfTrainerClasses               | 66                                     | 66                          |           |
    |  TrainerImageTable                    | 305654                                 | 305018                      | ✔ (graphics.trainers.sprites.front)          |
    |  NumberOfTrainerImages                | 92                                     | 92                          |           |
    |  TrainerPaletteTable                  | 30593C                                 | 305300                      | ✔ (graphics.trainers.palettes.front)          |
    |  TrainerMoneyTable                    | 31AEB8                                 |                             |           |
    |  DexSizeTrainerSprite                 | 71                                     | 71                          |           |
    |  TradeData                            | 338ED0                                 | 3388CC                      |           |
    |  NumberOfTrades                       | 4                                      | 4                           |           |
    |  PokedexAlphabetTable                 | 55C6A4                                 | 5593E8                      |           |
    |  PokedexLightestTable                 | 55C9DA                                 | 55971E                      |           |
    |  PokedexSmallestTable                 | 55CCDE                                 | 559A22                      |           |
    |  PokedexTypeTable                     | 0                                      | 0                           |           |
    ```
    
</details>
    

<br>

<h3> Other tools: </h3>

- [PGE](https://github.com/Gamer2020/PokemonGameEditor): this editor supports BPEI. to be tested.
- [OWM](https://github.com/kimwnasptd/OWM-Qt): editor for overworld sprites. supports BPEI.
- ~~[PoryMap](https://github.com/huderlem/porymap): alternative to AM. could be useful to fix maps tables in the BPEI.toml; to be tested.~~ (decompressed rom required)
- [GBAIntroManager](https://github.com/Sierraffinity/GBAIntroManager): to be tested. some fix required:
    <details>
    <summary>add this offsets to GBAIntroManager.ini</summary>

    ```
    [BPEI]
    GameName=Pokémon Smeraldo
    GameType=E
    ItemData=0x58000C
    NumberOfItems=376
    PokemonNames=0x317F8C
    NumberOfPokemon=411
    StartingPosition=0x84468
    IntroPokemonNumber1=0x31928
    IntroPokemonNumber2=0x30B10
    IntroPokemonPicture=0x130BB0
    StartingPCItem=0x5DCA48
    StartingMoney=0x845D0
    TitlescreenMusic=0xAAAFC
    ProfessorMusic=0x30876
    SkipGender1=0x30DC8
    SkipGenderTester=0x30FD9
    SkipGenderOriginal=0x30DCD
    SkipGender2=0x31220
    SkipGender3=0x12FACE
    SkipGender4=0x12FBBA
    TruckRemovedAddr=0x86011
    TruckRemovedTester=0xFB14C
    UnlockedTester=0x8447F
    [/BPEI]
    ```
    
    </details>
    

<br>

<br>
References/useful info:
[Forum in ita](https://www.pokemonhacking.it/showthread.php?tid=4014).<br>
scripting: https://www.pokecommunity.com/showthread.php?t=164276


