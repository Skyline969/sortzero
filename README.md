This script takes a single parameter - a directory of categories of ROMs to sort. Example:

/roms

/roms/GBA

/roms/GBA/Homebrew.gba

/roms/GBA/ROM 1.gba

/roms/GBA/ROM 2.gba

/roms/NES

/roms/NES/Awesome ROM.nes

/roms/NES/ROM 1.nes



It will then sort it to something along the lines of:

/roms

/roms/GBA

/roms/GBA/h/Homebrew.gba

/roms/GBA/r/ROM 1.gba

/roms/GBA/r/ROM 2.gba

/roms/NES

/roms/NES/a/Awesome ROM.nes

/roms/NES/r/ROM 1.nes


The script must have only one parameter passed to it. Caution is advised, as it will blindly sort any

directory passed into it. Do not pass a directory that you wouldn't want sorted!
