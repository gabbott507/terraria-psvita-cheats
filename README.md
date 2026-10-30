# Terraria PS Vita VitaCheat code

Tested code for the North American Terraria PS Vita release, title ID `PCSE00317`.

## Max HP sync

The tested VitaCheat code copies the character's max HP into current HP while enabled. It is off by default.

```text
_V0 Sync HP to Max HP
$8101 81A000D0 000000A6
$8800 00000000 00000000
$8501 81A000D0 000000A4
$8900 00000000 00000000
```

Copy `PCSE00317.psv` to `ux0:/vitacheat/db/PCSE00317.psv`, then restart Terraria to reload the cheat database. Enable **Sync HP to Max HP** in VitaCheat.

## Compatibility

- Game: Terraria for PS Vita, North American title ID `PCSE00317`
- Cheat plugin: VitaCheat with Pointer MOV support
- Tested by the requester with two characters
- Other regions, game versions, and cheat plugins are unverified

This repository contains the cheat text only; it does not include game files or save data.
