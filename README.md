# t430
 My T430 Coreboot rom

There are 2 bios files with names self explanatory;
Coreboot.rom is an Intel GPU rom and nVidia is to be flashed only on laptops with nVidia GPU.

to flash (with coreboot already installed):

`sudo flashrom -p internal:laptop=force_I_want_a_brick -w name_of_the_rom.rom `
