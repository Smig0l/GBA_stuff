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
    [BPEI]
    ROMName=Pokemon Smeraldo (Italiano)
    ItemData=58000C
    AttackNames=319140
    TMData=612BDC
    TotalTMsPlusHMs=58
    TotalTMs=50
    ItemIMGData=610FAC
    NumberOfItems=377
    NumberOfAttacks=354
    MoveTutorAttacks=611BA8
    NumberOfMoveTutorAttacks=32
    PokemonNames=317F8C
    NumberOfPokemon=412
    NationalDexTable=31D682
    SecondDexTable=31D34C
    HoenntoNationalDex=31D9B8
    PokedexData=568C80               ✔ (data.pokemon.stats)
    NumberOfDexEntries=387
    NumberOfRegionDex=202
    PokemonData=31FDCC
    AbilityNames=31B0DB             ✔ (data.abilities.name)
    NumberOfAbilities=78
    Pointer2PointersToMapBanks=84AB8
    MapLabelData=59DEEC
    NumberOfMapLabels=213
    PokemonFrontSprites=300DDC
    PokemonBackSprites=30227C
    PokemonNormalPal=30303C
    PokemonShinyPal=303DFC
    PokemonAnimations=309B50
    FrontAnimationTable=3293EC
    BackAnimTable=607464
    AnimDelayTable=329587
    IconPointerTable=57838C
    IconPalTable=578A6C
    CryTable=69A380
    CryTable2=69B538
    CryConversionTable=31F01C
    FootPrintTable=56BD64
    PokemonAttackTable=328D7C
    PokemonEvolutions=324D1C
    TMHMCompatibility=31E298
    TMHMLenPerPoke=8
    MoveTutorCompatibility=611BE4
    EnemyYTable=3006FC
    PlayerYTable=301B9C
    EnemyAltitudeTable=305790
    AttackData=31C298
    ContestMoveData=5888F4
    ContestMoveEffectData=58940C
    AttackDescriptionTable=619038
    AbilityDescriptionTable=31B4D4
    StarterPokemon=5AE994               ✔ (scripts.newgame.starters.pokemon)   
    StarterPokemonLevel=B118C
    StarterEncounterPokemon=3270A
    StarterEncounterPokemonLevel=32718
    AttackAnimationTable=2C9CF8
    BattleFrontierTrainers=5D2614
    SlateportBattleTentTrainers=5DA55C
    VerdanturfBattleTentTrainers=5DB158
    FallarborBattleTentTrainers=5dbbcc
    NumberOfBattleFrontierTrainers=300
    NumberOfSlateportBattleTentTrainers=30
    NumberOfVerdanturfBattleTentTrainers=30
    NumberOfFallarborBattleTentTrainers=30
    BattleFrontierPokemon=5D6304
    SlateportBattleTentPokemon=5DAB74
    VerdanturfBattleTentPokemon=5DB770
    FallarborBattleTentPokemon=5DC1E4
    NumberOfBattleFrontierPokemon=882
    NumberOfSlateportBattleTentPokemon=70
    NumberOfVerdanturfBattleTentPokemon=45
    NumberOfFallarborBattleTentPokemon=45
    BattleFrontierHeldItems=5CB7F8
    BattleFrontierBanList=60E836
    NumberOfBattlefrontierHeldItems=62
    IconPals=DDE1D8
    StartSearchingForSpaceOffset=E3D0B0
    FreeSpaceSearchInterval=100
    NumberOfEvolutionsPerPokemon=5
    NumberOfEvolutionTypes=15
    EvolutionName0=None
    EvolutionName1=Felicita
    EvolutionName2=Felicita (Giorno)
    EvolutionName3=Felicita (Notte)
    EvolutionName4=Livello
    EvolutionName5=Scambio
    EvolutionName6=Scambio con Ogg.
    EvolutionName7=Oggetto
    EvolutionName8=Atk > Def
    EvolutionName9=Atk = Def
    EvolutionName10=Atk < Def
    EvolutionName11=High Personality
    EvolutionName12=Low Personality
    EvolutionName13=Allow Pokemon Creation
    EvolutionName14=Create Extra Pokemon
    EvolutionName15=Bellezza Massima
    Evolution0Param=none
    Evolution1Param=evolvesbutnoparms
    Evolution2Param=evolvesbutnoparms
    Evolution3Param=evolvesbutnoparms
    Evolution4Param=level
    Evolution5Param=evolvesbutnoparms
    Evolution6Param=item
    Evolution7Param=item
    Evolution8Param=level
    Evolution9Param=level
    Evolution10Param=level
    Evolution11Param=level
    Evolution12Param=level
    Evolution13Param=evolvesbutnoparms
    Evolution14Param=level
    Evolution15Param=evolvesbasedonvalue
    EggMoveTable=32A7D8
    EggMoveTableLimiter=70464
    TrainerTable=30FA1C                 ✔  (data.trainers.stats)
    NumberOfTrainers=854
    TrainerClasses=30F698
    NumberOfTrainerClasses=66
    TrainerImageTable=305018            ✔ (graphics.trainers.sprites.front)
    NumberOfTrainerImages=92
    TrainerPaletteTable=305300          ✔ (graphics.trainers.palettes.front)
    DexSizeTrainerSprite=71
    TradeData=3388CC
    NumberOfTrades=4
    PokedexAlphabetTable=5593E8
    PokedexLightestTable=55971E
    PokedexSmallestTable=559A22
    PokedexTypeTable=0
    [/BPEI]
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


