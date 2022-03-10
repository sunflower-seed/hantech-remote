# hantech-remote
Infrared Codes for Hantech air-conditioner remote control
The Hantech A016-09KR2 is a monoblock air-conditioner sold by the german hardware store Hornbach.
It has an infrared remote to control several features of the device.

## Remote control
The remote uses the NEC Protocol.

![Sketch of remote control](https://github.com/sunflower-seed/hantech-remote/blob/main/remote_annotated.svg)
(Note: The Sketch is not a scale drawing)

| #Key  |Command Description   |NEC Code (hex)  |
|---|---|---|
| 1 | On/Off | `0x01FE39C6` | 
| 2 | Timer| `0x01FEF906` |
| 3 | Down| `0x01FEA956` |
| 4 | AC Mode | `0x01FEB946` |
| 5 | Up | `0x01FE29D6` |
| 6 | Fan Speed | `0x01FE6996` |
| 7 | Nightmode | `0x01FED926` |

## License
[CC-BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)
