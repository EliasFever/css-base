# THIS IS NOT AN IMPROVED VERSION.
I am just messing around with it and see what happens:3
- Chungus Studios.

# Counter Strike: Source

an open source port of the leaked 2007 Source engine leak of the award winner Counter Strike Source. 

This mod is orient to Community so everyone can grow the mod whit his contributions.
Currently this mod is in a pre-alpha state so don’t expected any class of bugs.

[![CircleCI](https://circleci.com/gh/FriskTheFallenHuman/css-community.svg?style=svg)](https://circleci.com/gh/FriskTheFallenHuman/css-community)

## :hammer: Building

1. Download and install [Visual Studio 2013](https://dl.bobpony.com/software/visualstudio/2013/).
2. Download and install the [Multibyte MFC Library](https://www.microsoft.com/en-gb/download/details.aspx?id=40770).
3. Run first `creategameprojects.bat` and build it this contains the mod dll need to run the mod.

## :heavy_exclamation_mark: Warning

Although this mod is based on SourcePlusPlus's CSS Port, some things will not work has expected.

## :bug: Bugs

- Prop physics are weird due that CS:S Uses sv_turbophysics.
- The flashbang doesn’t disappear sometimes.
- The Animation system used in the leak is the same in the HL2MP it used the base_playeranimstate so this animsystem don’t come whit a MP support so you can see the player making the walk anim but stuck at the first frame.
  The only way to fix this is redo the animation system to make work whit multiplayer_animstates.
- ~~The Dynamic crosshair it’s not the same to the he original CSS someone of the cvars don’t work.~~ :white_check_mark: Fixed
- Using the Bots may cause the game crash. 

## :mega: Contributing

Feel free to contribute to the project with pull requests. They will be reviewed and merged as fast as possible.

## :clipboard: Credits

|           **Valve**            |           Source Engine and Counter Strike Source            |
| :----------------------------: | :----------------------------------------------------------: |
| **Joshua Ashton And SCell555** |            **Original creator of SourcePlusPlus**            |
|          **Petercov**          | **Modified SourcePlusPlus's CSS (witch is based this port)** |
|         **NicolasDe**          |                 **For his amazing GameUI2**                  |
|        **TotallyMehis**        | **Creator of Zombie Master: Reborn and some code that is used here** |
|         **Spirrwell**          |                   **FMOD Implementation**                    |
|      **Kenney Vleugels**       |                 **Original Crosshair Pack**                  |
|       **TF2ClassicTeam**       |                    **Hud Crosshair code**                    |
