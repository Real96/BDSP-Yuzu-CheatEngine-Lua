# BDSP-CheatEngine-Lua
Lua script for RNG abusing in Pokémon Brilliant Diamond and Shining Pearl on Yuzu/Ryujinx emulator via Cheat Engine!

![Cleffa](https://user-images.githubusercontent.com/20956021/145038320-37ae9125-aa91-4ebe-9d3a-687d8043e589.png)

## Features
* Rng info checking
* Trainer info checking
* Wild Pokemon info checking
* Breeding info checking
* Roamer Pokemon info checking
* Party Pokemon info checking
* Box Pokemon info checking

## Requirements
* [Cheat Engine](https://www.cheatengine.org/downloads.php)
* [Yuzu](https://yuzu-emu.org/downloads/)/[Ryujinx](https://ryujinx.org/download)
* Updated game to version 1.1.1+

## Usage
1) Open Yuzu/Ryujinx, run the game and pause it at the title screen
2) Open Cheat Engine, click on `Edit > Settings`, select `Scan Settings` and check `MEM_MAPPED` option
3) Click on `File > Open Process` and select Yuzu/Ryujinx process (Yuzu will look like `xxxx-yuzu xxx | game name`, Ryujinx will look like `xxxx-Ryujinx x.x.xxxx - game name`)
4) Click on `Table > Show Cheat Table Lua Script`. A new window called `Lua Script: Cheat Table` will appear
5) Open `BDSP_RNG (v1.x.x).lua` with a text editor, copy all its content and paste it in the window opened before
6) Click `Execute Script`. It will freeze for some seconds, just wait until all the rng info will be printed in a new window

## Notes
* To change the info view tab mode, press the keys shown in the script output
* If you want to stop the script, press keyboard key 0 or keyboard key NumPad 0. It won't stop otherwhise
* If you want to restart the game, do what's written above and then restart the game and the script. It won't work otherwhise
* To avoid text flickering, be sure to enlarge enough the `Lua Engine` window

## Credits:
* [Cheat Engine](https://github.com/cheat-engine/cheat-engine) devs
* [Yuzu](https://github.com/yuzu-emu/yuzu)/[Ryujinx](https://github.com/Ryujinx/Ryujinx) devs
* [zaksabeast](https://github.com/zaksabeast) for the research and for his great Rng Switch tool [CaptureSight](https://github.com/zaksabeast/CaptureSight/) (part of the code is taken from there)
* [Admiral-Fish](https://github.com/Admiral-Fish) for the research and for his great app [PokeFinder](https://github.com/Admiral-Fish/PokeFinder) always up to date
* [SteveCookTU](https://github.com/SteveCookTU) for the research and for dumping Items, Moves and Abilities tables
* [SciresM](https://github.com/SciresM), [Kaphotics](https://github.com/kwsch) and all the other Pokemon researchers!
