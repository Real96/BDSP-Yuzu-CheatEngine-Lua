# BDSP-CheatEngine-Lua
Lua script for RNG abusing in Pokémon Brilliant Diamond and Shining Pearl on Yuzu/Ryujinx emulator via Cheat Engine!

![image](https://user-images.githubusercontent.com/20956021/143800907-9998e7ec-f29d-42fc-a672-1ffcac684bc2.png)

## Requirements
* [Cheat Engine](https://www.cheatengine.org/downloads.php)
* [Yuzu](https://yuzu-emu.org/downloads/)/[Ryujinx](https://ryujinx.org/download)
* Updated game to version 1.1.1

## Usage
* Open Yuzu/Ryujinx, run the game and pause it at the title screen
* Open Cheat Engine, click on `Edit > Settings`, select `Scan Settings` and check `MEM_MAPPED` option
* Click on `File > Open Process` and select Yuzu/Ryujinx process (Yuzu will look like `xxxx-yuzu xxx | game name`, Ryujinx will look like `xxxx-Ryujinx x.x.xxxx - game name`)
* Click on `Table > Show Cheat Table Lua Script`. A new window called `Lua Script: Cheat Table` will appear
* Open `BDSP_RNG.lua` with a text editor, copy all its content and paste it in the window opened before.
* Click `Execute Script`. It will freeze for a bit, just wait until it will print all the rng info in a new window
* If you want to stop the script press 0 or NumPad 0. It won't stop otherwhise

## Note
In noisy areas advances will be too fast for Cheat Engine. So, in case it freezes, just pause Yuzu/Ryujinx and wait until Cheat Engine unfreezes to unpause the emulator.

## Credits:
* [Cheat Engine](https://github.com/cheat-engine/cheat-engine) devs
* [Yuzu](https://github.com/yuzu-emu/yuzu)/[Ryujinx](https://github.com/Ryujinx/Ryujinx) devs
* zaksabeast for his great Rng Switch tool [CaptureSight](https://github.com/zaksabeast/CaptureSight/) (part of the code is taken from there)
* Admiral-Fish for his great app [PokeFinder](https://github.com/Admiral-Fish/PokeFinder) always up to date
* [SciresM](https://github.com/SciresM), [Kaphotics](https://github.com/kwsch) and all the other Pokemon researchers!
