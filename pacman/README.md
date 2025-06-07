# Pac-Man Tile
## 8 bit throwback

### Current rules:

| Pac-Man |
---------
| On play: Draw three Ghosts |
| Once per turn: Move to an |
| adjacent empty slot |
| Trigger: Overwrite an |
| adjacent ghost with this |

| Ghost |
--------- 
| Virtual |
| Mandatory once per turn: |
| move to an adjacent empty |
| slot. Then if able, overwrite |
| an adjacent Pac-Man with |
| this & skip your next turn |


### Issues:
- Wordy
- Want a way to justify printing all four Ghosts
- Very busy. Might be too much for everyone to do on their turns
- Lot of moving tiles. Maybe too powerful to be able to move 4+ tiles at once
- Not great once Pac-Man / all the Ghosts are destroyed
- No card for fruit

### Possible solutions (in no particular order):
- Change draw from three to four
    - Dislike, as most of the time you are discarding down to three anyway
    - Some effects change hand size (e.g., Reliquary Tile), but I'd like the tile to be self-contained
    - Maybe have ghost not count against hand size.
- Change draw to one ghost per player
    - Not particularly popular. Too easy to corner Pac-Man
- Change draw to once per turn create a Ghost
    - No permanent ghost destruction
- Tie movement to triggered abilities



| Pac-Man |
---------
| On play: Draw four ghosts |
| Trigger: overwrite an |
| adjacent Ghost with this |
| - or - move this to an | 
| adjacent empty slot |


| Ghost |
--------- 
| Virtual |
| While held: +1 hand size |
| Trigger: If able, overwrite |
| an adjacent Pac-Man with | 
| this & skip your next turn. |
| else, move to an adjacent slot |


| Cherries |
---------
| On destroy: take an |
| extra turn |
| Pac-man may overwrite this |
| tile when moving |