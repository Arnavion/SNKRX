



# SNKRX

[SNKRX](https://store.steampowered.com/app/915310/SNKRX/) is an arcade shooter roguelite where you control a snake of heroes that automatically attack nearby enemies.
Combine different heroes to unlock class bonuses and create unique builds, and steer your unstoppable party as they ravage through endless waves of enemies.

https://user-images.githubusercontent.com/409773/119258159-ea982b00-bb9e-11eb-8082-37e2c65591ea.mp4

[**Check it out on Steam!**](https://store.steampowered.com/app/915310/SNKRX/)

### Modifications to the original version

The original version can be found [here.](https://github.com/a327ex/SNKRX) This repository contains patches rebased on top of upstream's master. Currently there are two patches:

1. Remove Steam API calls and checked-in love binaries.

1. Fix a crash in the code that tests for big-integer support that requires Lua 5.4, and thus crashes on distros where love uses luajit which is Lua 5.1

### Running

Download this repository, `cd` into it and then run `love .` Enjoy!

### LICENSE

All assets have their specific licenses and they are linked to in the game's credits. All code is under the MIT license.
