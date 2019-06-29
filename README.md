# minecraft
Miscellaneous Minecraft helper and management scripts

## Scripts (MSM)

These scripts work in conjunction with [MSM](http://msmhq.com/). As MSM is no
longer being updated, the goal is to convert some of these scripts to work
independently. The RCON thread safety bug [72390](https://bugs.mojang.com/browse/MC-72390) has been fixed recently, so that is
one option.

* **tps_check** — Fetch the current TPS of the server

## Scripts (Agnostic)

These scripts will run independently of any Minecraft server manager, but may
require extra configuration to locate the game files.

* **mc_make_tp** — Create `.mcfunction` commands for custom teleports

## Copyright and License

©2011–2019 Lukahna

All software in this repository is licensed under the GPL v3.0
unless otherwise specified. Please see `LICENSE` for the full text.
