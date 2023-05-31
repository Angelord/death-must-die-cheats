# Cheat Codes

Some codes require parameters. These are listed after the code, wrapped in '<>'.

Some parameters are optional, if they have default values they will be denoted with '=' (<level=1>), otherwise the parameter is prefixed with '?' (<?god>).

| code                                  | description                                                                              | example                     | 
|---------------------------------------|------------------------------------------------------------------------------------------|-----------------------------|
| gb \<boon> \<rarity> \<level=1>       | Gives a boon instantly                                                                   | gb Meteor myth 3            | 
| rb \<boon>                            | Removes a boon.                                                                          | rb Meteor                   | 
| gi \<affix1:level> \<affix2:level>    | Gives a random item with specified affixes. Can optionally specify level for each affix. | gi hpr:5 aprc               | 
| lb \<boon> \<levels>                  | Gains 'levels' for the boon.                                                             | lb Meteor 2                 | 
| mg                                    | Makes the player invulnerable to damage.                                                 | -                           | 
| ug                                    | Removes the invulnerability from mg.                                                     | -                           | 
| mc                                    | Makes the player **chonky**, giving him 1000 hp.                                         | -                           | 
| die                                   | Kills you instantly.                                                                     | -                           | 
| lvl \<levels=1> \<?god>               | Gain 'levels' from 'god'. If god is not specified it will be random.                     | lvl 3                       | 
| slvl \<level>                         | Sets the player at 'level' without offering boons.                                       | slvl 15                     | 
| min \<minute>                         | Sets the run time. Minute is in format mm:ss.                                            | min 15:20                   | 
| s \<monster> \<count=1>               | Spawns 'count' monsters with code 'monster'.                                             | s Skeleton 10               | 
| nospawn                               | Disables monster spawning.                                                               | -                           | 
| setstat \<boon> \<stat> \<value>      | Sets 'stat' of 'boon' to 'value'.                                                        | setstat Meteor pow 20       | 
| modstat \<stat> \<modifier> \<?group> | Adds 'modifier' to 'stat' of 'group'. If group is empty will affect root.                | modstat spd 1.5 Offensive   | 
| pstat \<stat> \<value>                | Sets 'stat' of player to 'value'.                                                        | pstat mvm 12                | 
| takedmg \<amount>                     | Deals 'amount' damage to player.                                                         | takedmg 100                 | 
| tof                                   | Stops the run timer.                                                                     | -                           | 
| ton                                   | Starts the run timer.                                                                    | -                           | 
| kal                                   | Kills all monsters.                                                                      | -                           | 
| da                                    | Disables the player's attack.                                                            | -                           | 
| da                                    | Disables the player's attack.                                                            | -                           | 
| ea                                    | Enables the player's attack.                                                             | -                           | 
| dd                                    | Disables level-up dialogue.                                                              | -                           | 
| ed                                    | Enables level-up dialogue.                                                               | -                           | 
| ed                                    | Enables level-up dialogue.                                                               | -                           | 
| sc                                    | Spawns a chest at the player position.                                                   | -                           | 
| si \<monster> \<count=1>              | Generates 'count' item drops from 'monster'.                                             | si Summoner 3               | 
| spt \<time>                           | Sets the profile's total playtime. Format is hh:mm.                                      | spt 3:30                    | 
| stopxp                                | Disables xp gain from gems.                                                              | -                           | 
| cin                                   | Enters 'cinematic' mode. Hides hp bars, dmg numbers and stops xp gain.                   | -                           | 
| loc                                   | Sets the game's locale.                                                                  | -                           | 
| eval \<expression>                    | Evaluates a story conditional expression.                                                | eval "talk_sor or talk_kni" | 
| rshop                                 | Refreshes the shop offers.                                                               | -                           | 
| goldpls \<amount>                     | Gives you gold.                                                                          | goldpls 1000                | 
| srec                                  | Starts recording a sequence of commands.                                                 | -                           | 
| erec                                  | Ends a command recording started with 'srec'.                                            | -                           | 
| play                                  | Plays the command sequence recorded with 'srec' and 'erec'.                              | -                           | 
| stun                                  | Applies a stun status to all enemies.                                                    | -                           | 
| encl                                  | Starts an enclosure (black fires).                                                       | -                           | 
| sav                                   | Forces a save on profile data.                                                           | -                           | 
| rs                                    | Resets the story state to the beginning.                                                 | -                           | 
| ps                                    | Progress the story through one run.                                                      | -                           | 
| ach \<achievement>                    | Unlocks the achievement specified.                                                       | ach Unlock_Sor              | 
| win                                   | Wins the run.                                                                            | -                           | 
| lose                                  | Loses the run.                                                                           | -                           | 
| asp \<status>                         | Applies a status to the player.                                                          | asp ss_stamina              | 
| ase \<status>                         | Applies a status to all active enemies.                                                  | ase feared                  | 
| tev \<boon> \<count=1>                | Triggers an event-based boon 'count' times.                                              | tev Blades 10               | 
