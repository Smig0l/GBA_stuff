# GBA_stuff
<h1> tools that i am using: </h1>

- [HexManiacAdvance](https://github.com/haven1433/HexManiacAdvance)
- [mGBA - GBA emulator](https://github.com/mgba-emu/mgba)
- [Advanced Map Editor](http://getam.no-ip.info/?ver=1.95)

<h2> Known issues with HMA: </h2>
Speaking with the developer at the moment only "BPEE" is supported (pokemon emerald english version).

But we can [edit](https://github.com/haven1433/HexManiacAdvance/wiki/TOML-and-You:-How-Metadata-works) the .toml file that is created (named "gbaromname.toml") when the tool is started.<br>
For the correct addresses we can refer to [this](https://github.com/Gamer2020/PokemonGameEditor/blob/master/roms.ini).

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

