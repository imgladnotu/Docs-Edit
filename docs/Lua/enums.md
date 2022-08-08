# Enums

Enums are used to represent a set of named values.
You can acces them globally by using `Enums.Buttons.IN_ATTACK` for example.

## Buttons

Button bitmask for UserCmd.

| Key | Value |
| :-: | :-: |
| IN_ATTACK | `1 << 0` |
| IN_JUMP | `1 << 1` |
| IN_DUCK | `1 << 2` |
| IN_FORWARD | `1 << 3` |
| IN_BACK | `1 << 4` |
| IN_USE | `1 << 5` |
| IN_CANCEL | `1 << 6` |
| IN_LEFT | `1 << 7` |
| IN_RIGHT | `1 << 8` |
| IN_MOVELEFT | `1 << 9` |
| IN_MOVERIGHT | `1 << 10` |
| IN_ATTACK2 | `1 << 11` |
| IN_RUN | `1 << 12` |
| IN_RELOAD | `1 << 13` |
| IN_ALT1 | `1 << 14` |
| IN_ALT2 | `1 << 15` |
| IN_SCORE | `1 << 16` |
| IN_SPEED | `1 << 17` |
| IN_WALK | `1 << 18` |
| IN_ZOOM | `1 << 19` |
| IN_WEAPON1 | `1 << 20` |
| IN_WEAPON2 | `1 << 21` |
| IN_BULLRUSH | `1 << 22` |
| IN_GRENADE1 | `1 << 23` |
| IN_GRENADE2 | `1 << 24` |
| IN_ATTACK3 | `1 << 25` |

## ClientFrameStage

| Key | Value |
| :-: | :-: |
| FRAME_UNDEFINED | `-1` |
| FRAME_START | `0` |
| FRAME_NET_UPDATE_START | `1` |
| FRAME_NET_UPDATE_POSTDATAUPDATE_START | `2` |
| FRAME_NET_UPDATE_POSTDATAUPDATE_END | `3` |
| FRAME_NET_UPDATE_END | `4` |
| FRAME_RENDER_START | `5` |
| FRAME_RENDER_END | `6` |

## Fonts

| Key | Value |
| :-: | :-: |
| FONT_ESP | `0` |
| FONT_ESP_NAME | `1` |
| FONT_ESP_COND | `2` |
| FONT_ESP_PICKUPS | `3` |
| FONT_MENU | `4` |
| FONT_INDICATORS | `5` |
| FONT_IMGUI | `6` |
| FONT_OSRS | `7` |
