# Minecraft-Server 1.19.x

## [General Server Changes]:
~~~
- Bedrock edition clients can join
- Any client 1.19 - 1.19.3 can join (1.19.x)
- World is pre-generated to ensure minimal lag
- Ground / unwanted entities are regularly cleared
~~~

## [Gameplay Changes]:
~~~
- Players will slowly gain hearts over time by killing hostile mobs. These
additional hearts will reset if you die.
- Silk touch can pick up spawners
~~~

## [Permissions]:
~~~
- Tpa commands (/tpa, /tpaccept, /tpdeny)
- Private chat commands (/msg, /r, /whisper)
- Ignore players (/ignore, /unignore)
- Warp commands (/spawn, /warps)
- Teleport to previous location (/back) (does not work with deaths)
- Random teleport location (/rtp) (30 minute cooldown)
- RPGHP Commands (/hp)
~~~

## [Combat mechanics and physics have been reverted to older versions!]
### [Notable changes]:
~~~
- Attack indicator will no longer display
- Attack cooldown has been disabled
- Player collisions have been disabled
- Attack sounds have been disabled
- Sword sweep has been disabled (Sweeping edge still works)
- Projectile random offset has been disabled
- Bow boosting has been disabled
- Shields have been disabled

- Players are able to strafe, and w tap properly (experimental)

- Players can now block (shields are automatically applied by holding right click with a sword)
- Blocking with a will reduce damage by 50%

- Projectile knockback has been added

- Player regen has been reverted to its 1.7.10 values
- Axe/tool damage has been reverted to 1.7.10 values
- Fishing rods have been reverted to their 1.7.10 values (reach, velocity, calculation)
- Notch apples can be crafted and have their 1.7.10 values
- Armor strengths have been reverted to their 1.7.10 values (durability remains untouched)

- Potion effects have been reverted to their 1.8 values
- Entity burning tick has been reverted to its 1.8 value
- Player knockback has been reverted to 1.8 values
- Critical hits have been reverted to their 1.8 values
~~~

## [TODO]:
~~~
- Death chest plugin
- Custom /help plugin
- Swap to other RTP plugin that I was originally using
- Re-configre clear lag and re-enable it at some point
- Users can claim land and protect chests (Gameplay)
- Multiverse spawn in voidworld with separate inventory than overworld, nether, and end
- Display player health next to name above player head (Server)

- Custom ban message plugin

- Proximity push to talk voice chat is available using the "Simple Voice Chat" mod! (Server)
- VR support plugin

- Chat reporting / signatures have been disabled (For vanilla players as well!)
- World border is 5000 blocks in every direction. May be updated in the future.

- Anticheat
~~~

