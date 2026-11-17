# Licence of this data

Rune Advisor is a fan-made tool. It is not affiliated with or endorsed by Jagex Ltd. RuneScape is a trademark
of Jagex Ltd.

Created using intellectual property belonging to Jagex Limited under the terms of Jagex's Fan Content Policy.
This content is not endorsed by or affiliated with Jagex.

| What | Where | Licence |
|---|---|---|
| Game data built from the RuneScape Wiki, and the project's hand-written tables | everything not listed below | CC BY-NC-SA 3.0, see `LICENSE` |
| Quest and achievement definitions read from the game client | `game_configs/` | Jagex's; not licensed by this project, see below |

## Data from the RuneScape Wiki

Most files here are produced from the [RuneScape Wiki](https://runescape.wiki/) (drop tables, shops, recipes,
equipment, rates taken from its guides, calculator tables and so on) and are the work of the wiki's
contributors, used and shared under the
[Creative Commons Attribution-NonCommercial-ShareAlike 3.0](https://creativecommons.org/licenses/by-nc-sa/3.0/)
licence. Whoever redistributes them must keep this attribution, share changes under the same licence, and not
use them commercially.

## Hand-written tables

Tables written by hand for this project (training rates, reset and claim schedules, conversions, shop
restocking and the like), largely from what the wiki's pages say, are shared by the Rune Advisor authors
under the same licence, so that everything outside `game_configs/` has one licence and one attribution.

## Game definitions

`game_configs/` holds quest and achievement definitions as the game client provides them through Jagex's
plugin API. They belong to Jagex Ltd. This project claims no rights in them and grants none.

## The program

The planner that reads this data is a separate work under GPL-3.0-or-later, in its own repository. The GPL
does not apply to this data, and this data's non-commercial condition does not apply to the code.
