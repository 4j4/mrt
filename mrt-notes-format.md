MRT Notes

`|cffRRGGBB...|r` - All text inside this code ("..." in current example) will be colored, where RR,GG,BB - color code in hex format (00..ff). Select any part of the note and use preinstalled color from dropdown for easy usage.

`{D}...{/D}` - All text inside this code ("..." in the current example) will be shown only for players with Damage specialization.

`{H}...{/H}` - All text inside this code ("..." in the current example) will be shown only to players with Healer specialization.

`{T}...{/T}` - All text inside this code ("..." in the current example) will be shown only to the players with Tank specialization.

`{spell:17}` - This example will be replaced with the spell icon (Spell 17, Powerword shield). You can use any ingame spell or you can select one from predefined list

`{self}` - This example will be replaced with personal note. You can place it anywhere. By default personal note will be shown after general note.

`{p:JaneD,JennyB-HowlingFjord}...{/p}` - All text inside this code ("..." in current example) will be shown only for players JaneD and JennyB (current example). You can use any numbers of players.

`{!p:Leeroy,Juron}...{/p}` - All text inside this code ("..." in current example) will be shown for all players, except Leeroy and Juron (current example). You can use any numbers of players.

`{icon:Interface/Icon/inv_hammer_unique_sulfuras}` - This example will be replaced with Sulfuras icon. You can use any ingame icon.

`{c:Palading,Priest}...{/c}` - All text inside this code ("..." in current example) will be shown only for selected classes (Paladin and Priest in this example). You can use any numbers of classes.

`{!c:Mage,Hunter}...{/c}` - All text inside this code ("..." in current example) will be shown for all players, except selected classes (Mage and Hunter in this example). You can use any numbers of classes.

`{g2}...{/g}` - All text inside this code ("..." in current example) will be shown only to players in second group (current example). You can use any numbers of groups.

`{!g34}...{/g}` - All text inside this code ("..." in current example)will be shown for all players except in groups 2 and 3 (current example). You can use any numbers of groups.

`{time:2:45}` - This example will be replaced with dynamic timer for selected moment during bossfight.

`{p2}...{/p}` - All text inside this code ("..." in current example) will be shown only during specific boss phase (second phase in current example). Only with addons BigWigs or DBM.

`{time:1:06,p2}` - This example will be replaced with dynamic timer for selected moment during bossfight. Timer will be active only during specific boss phase (second phase in current example). Only with addons BighWigs or DBM.

`{time:0:30,SCC:17:2}` - This example will be replaced with dynamic  timer for selected moment during bossfight. Timer will start only after fulfillment of condition. Condition format "event:spellID:counter". 
Combat log events: 
- `SCC` - spell cast success 
- `SCS` - spell cast start 
- `SAA` - aura applied on any target
- `SAR` - aura removed from any target
 
`Counter` use number of repetitions of this event from the beginning of the fight. User 0 for every event.
