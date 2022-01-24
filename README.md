# Reviung41 Keymaps (zmk, nice!nano, colemak)
![reviung41](reviung41.png)

```
Keyboard: Reviung41
Default Layer: Colemak
Keyboard Firmware: ZMK
Board: Nice!Nano
Microcontroller: Nordic nRF52840

Input Language (PC)
(the default layout for given language)
Layout Display Name: Turkish Q
Layout Text: Turkish Q
```

## Reviung41
### COLEMAK LAYER (default)
``` 
,----------------------------------------------+          +------------------------------------------------.
|   TAB    |  Q   |   W  |   F  |   P  |   G   |          |   J  |   L  |   U  |   Y  |   ;  |     BSPC     |
|----------+------+------+------+------+-------+          +------+------+------+------+------+--------------|
|   LCTRL  |  A   |   R  |   S  |ARRW_T|   D   |          |   H  |   N  |   E  |   I  |   O  |  RCTL_DQUO   |
|----------+------+------+------+------+-------+          +------+------+------+------+------+--------------|
| LSFT_CAPS|LALT_Z|LCTL_X|LSFT_C|   V  |   B   |          |   K  |   M  |RSFT ,|RCTL .|   /  |   RSFT_ENT   |
|----------+------+------+------+------+-------+          +------+------+------+------+------+--------------|
                            | ALT  | Lower_up |  Space_spc  | Raise_down | WIN  |
                                +-------------/             \--------------+
```

#### LOWER LAYER
```
,---------------------------------------------------+         +------------------------------------------.
|  ESC  |       |       |         |       |         |         |  (   |   )  |   =  |   &  |   |  |  DEL  |
|-------+-------+-------+---------+-------+---------+         +------+------+------+------+------+-------|
|       |       |       |   <     |   >   |         |         |  {   |   }  |   _  |   $  |   #  |   `   |
|-------+-------+-------+---------+-------+---------+         +------+------+------+------+------+-------|
|       |       |       |         |       |         |         |  [   |   ]  |   ^  |   ~  |   \  |  END  |
|-------+-------+-------+---------+-------+---------+         +------+------+------+------+------+-------|
                                   | ____ | ____ |      ENTER     | ____  | ____ |
                                   +-------------/                \--------------+
```

#### RAISE LAYER
```
,-----------------------------------------------+         +------------------------------------------.
|  ESC  |   /  |   1   |    2   |   3   |   -   |         |  F1  |  F2  |  F3  |  F4  |      |       |
|-------+------+-------+--------+-------+-------+         +------+------+------+------+------+-------|
|       |   *  |   4   |    5   |   6   |   +   |         |  F5  |  F6  |  F7  |  F8  |      |       |
|-------+------+-------+--------+-------+-------+         +------+------+------+------+------+-------|
|cps_wrd|   %  |   7   |    8   |   9   |   0   |         |  F9  |  F10 |  F11  | F12 |      |       |
|-------+------+-------+--------+-------+-------+         +------+------+------+------+------+-------|
                                | ____ | ____ |     BSPC     | ____  | ____ |
                                +-------------/              \--------------+
```

#### SPACE LAYER
```
,-------------------------------------------------- -+         +------------------------------------------.
|   ESC  |   !    |   @   |   €     |    £  |   Ğ    |         |      |      |   Ü  |      |  :   |  DEL  |
|--------+--------+-------+---------+-------+--------+         +------+------+------+------+------+-------|
|        |        |       |    Ş    |   ₺   |  SPACE |         |   <  |   >  | S(ı) |   I  |  Ö   |  '    |
|--------+--------+-------+---------+-------+--------+         +------+------+------+------+------+-------|
|        |        |       |    Ç    |       |        |         |      |      |      |      |      |       |
|--------+--------+-------+---------+-------+--------+         +------+------+------+------+------+-------|
                                    | ____ | ____ |     _______      | ____  | ____ |
                                    +-------------/                \--------------+
```
#### NAVIGATION LAYER
```
,---------------------------------------------------+         +------------------------------------------.
|       |       |       |         |       |         |         |C_PREV| PGUP |  UP  |      |      |       |
|-------+-------+-------+---------+-------+---------+         +------+------+------+------+------+-------|
|       |       |       |         |NAVI_T |         |         | HOME | LEFT | DOWN | RGHT | END  | MPLY  |
|-------+-------+-------+---------+-------+---------+         +------+------+------+------+------+-------|
|       |       |       |         |       |         |         |C_NEXT|PGDOWN|      |VLDOWN| VLUP | MUTE  |
|-------+-------+-------+---------+-------+---------+         +------+------+------+------+------+-------|
                                   | ____ | ____ |                | ____  | ____ |
                                   +-------------/                \--------------+
```


#### ADJUST LAYER
```
,-------------------------------------------------------- -+         +-----------------------------------------.
| RGB BRI+ | RGB SAT+ | RGB HUE+ | RGB ANI+ |    | RGB TOG |         |  BT1  | BT2 | BT3 | BT4 | BT5  | BT CLR |
|----------+----------+----------+----------+----+---------+         +--- ---+-----+-----+-----+------+-- -----|
| RGB BRI- | RGB SAT- | RGB HUE- | RGB ANI- |    |         |         |       |     |     |EP_ON|EP_OFF| EP_TOG |
|----------+----------+----------+----------+----+---------+         +-------+-----+-----+-----+------+--------|
|          |          |          |          |    |         |         | RESET |     |     |O_USB|O_BLE |OUT_TOG |
|----------+----------+---------+-----------+----+---------+         +-------+-----+-----+-----+------+--------|
                                         | ____ | ____ |     _______      | ____  | ____ |
                                          +-------------/                \--------------+
```