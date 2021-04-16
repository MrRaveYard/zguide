# Feature Overview

## General
/ | GZDoom 4.6 | Zandronum 3.0.1
------------ | ------------- | -
Base (G)ZDoom | Latest|ZDoom 2.8pre-441-g458e1b1 / GZDoom 1.8.6|
OpenGL | 3.3+ | 2.0+ (?)
Vulkan | ✔️|❌
Softpoly |✔️|❌
Truecolor Soft. Renderer |✔️|❌


## ACS
ACS Features | GZDoom 4.6 | Zandronum 3.0.1
------------ | ------------- | -
Event scripts|❌|✔️
Kill scripts|✔️|✔️
Script scope int arrays|✔️|❌(Crash)

##### If not present, these do nothing and their return value is 0, unless specified otherwise

ACS Functions | GZDoom 4.6 | Zandronum 3.0.1
------------ | ------------- | -
Polyobj_MoveTo|✔️|❌ (Crash online)
Polyobj_OR_MoveTo|✔️|❌ (Crash online)
ScriptCall | ✔️|❌


Zandronum ACS Functions | GZDoom 4.6 | Zandronum 3.0.1
------------ | ------------- | -
RequestPuke|❌|✔️
AnnouncerSound|❌|✔️
BeginDBTransaction|❌|✔️
ConsoleCommand|❌|✔️
ConsolePlayerNumber|❌|✔️
CountDBResults|❌|✔️
EndDBTransaction|❌|✔️
FreeDBResults|❌|✔️
GameType|✔️(Limited?)|✔️
GetDBEntries|❌|✔️
GetDBEntry|❌|✔️
GetDBEntryRank|❌|✔️
GetDBEntryString|❌|✔️
GetDBResultKeyString|❌|✔️
GetDBResultValue|❌|✔️
GetDBResultValueString|❌|✔️
GetGameModeState|❌|✔️
GetInvasionState|❌|✔️
GetInvasionWave|❌|✔️
GetPlayerAccountName|❌|✔️
GetPlayerLivesLeft|❌|✔️
GetTeamProperty|❌|✔️
GetTimeProperty|❌|✔️
IncrementDBEntry|❌|✔️
IsNetworkGame|❌|✔️
IsOneFlagCTF|❌|✔️
KickFromGame|❌|✔️
NamedRequestScriptPuke|❌|✔️
PlayerArmorpoints|❌|✔️
PlayerHealth|❌(Maybe?)|✔️
PlayerIsLoggedIn|❌|✔️
PlayerIsSpectator|❌|✔️
PlayerTeam|❌|✔️
RequestScriptPuke|❌|✔️
ResetMap|❌|✔️
SetActivatorToPlayer|❌(Maybe?)|✔️
SetDBEntry|❌|✔️
SetDBEntryString|❌|✔️
SetDeadSpectator|❌|✔️
SetPlayerLivesLeft|❌|✔️
SortDBEntries|❌|✔️
Strftime|❌|✔️
SystemTime|❌|✔️

## Multiplayer


Multiplayer features | GZDoom 4.6 | Zandronum 3.0.1
------------ | ------------- | -
Architecture|Peer to peer (supports routing traffic through single peer)|UDP Client/Server
Checksum loaded WADs|❌|✔️(detects protected lumps)
Dedicated server|❌|✔️
Load game|✔️(on startup, must be sent to each peer)|❌
Master server|❌(unofficial connectors)|✔️
Max players|8|64
Port|5029|10666
Player skins|✔️|✔️
Reconnect to game|❌|✔️
Save game|✔️|❌


Built in gamemodes | GZDoom 4.6 | Zandronum 3.0.1
------------ | ------------- | -
Coop|✔️|✔️
Survival (limited lives)|❌|✔️
Deathmatch |✔️|✔️
Team Deathmatch |✔️ (probably?)|✔️
Last Man Standing |❌|✔️
Team Last Man Standing |❌|✔️
CTF, One flag CTF, Skulltag |❌|✔️



## ZScript

ZScript features | GZDoom 4.6 | Zandronum 3.0.1
------------ | ------------- | -
ZScript | ✔️|❌ (ZScript lumps are ignored)

