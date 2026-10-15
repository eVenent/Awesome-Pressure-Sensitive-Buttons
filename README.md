# Awesome Pressure-Sensitive Buttons [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
>This list is a collection of tools, projects, images and resources conforming to the [Awesome Manifesto](https://github.com/sindresorhus/awesome/blob/main/awesome.md).

Feel free to **contribute** / **star** / **fork** / **pull request**. Any **recommendations** and **suggestions** are welcome.

## About
> Pressure-sensitive buttons (or analog buttons) detect the exact amount of force a player applies, moving beyond standard "on/off" digital switches. While common on older console face buttons (like the PS2, Xbox OG and PS3), modern controllers mostly restrict this tech to the left and right shoulder triggers.

## Devices
| Controller | Console | Keyboard |
| ------------- | ------------- | -- |
| NeGcon | Nintendo DS touchpad | Wooting one |
| Xbox OG | iPhone generations with 3D Touch | Wooting two |
| DualShock 2 | Android devices with pressure touch| Razer Huntsman V2 Analog |
| DualShock 3 | | Razer Huntsman Mini Analog |
| Steam Deck | | Razer Tartarus Pro |
| Steam Controller | | SteelSeries Apex Pro |

### How They Work
Instead of simply opening or closing a circuit, these inputs translate physical force into a shifting electrical current using two main methods:
- **Force-Sensitive Resistors**: Used under rubber face buttons. Pressing harder squishes a conductive pad, increasing its surface contact with a circuit board. This lowers electrical resistance and signals a harder press.
- **Potentiometers**: Used in modern triggers. Pulling the trigger slides a mechanical component along a variable resistor, measuring the precise depth of the pull.

### Key Benefits
- **Granular Vehicle Control**: Allows precise throttle and braking adjustments in racing games, mimicking real gas pedals.
- **Nuanced Combat**: Enables multi-stage actions, such as lightly holding a button to aim a weapon and pressing harder to fire.
- **Dynamic Movement**: Adjusts character speed smoothly from a slow creep to a full sprint based entirely on finger pressure.
- **Variable Action Strength**: Distinguishes between light and heavy attacks, or short and long passes, without needing extra buttons.

## Supported Games:
- [Grand Theft Auto III](https://silent.rockstarvision.com/uploads/GInputIII.zip) - GInput
- [Grand Theft Auto: Vice City](https://silent.rockstarvision.com/uploads/GInputVC.zip) - GInput
- [Grand Theft Auto: San Andreas](https://silent.rockstarvision.com/uploads/GInputSA.zip) - GInput
  
» [List of PC games that support pressure-sensitive buttons
](https://www.pcgamingwiki.com/wiki/List_of_games_that_support_pressure-sensitive_buttons)

» [List of console games that support pressure-sensitive buttons
](https://emulation.gametechwiki.com/index.php/List_of_console_games_that_support_pressure-sensitive_buttons)

## Tools
#### Free
- [PadForge](https://github.com/hifihedgehog/PadForge) - Supports DualShock 2, Xbox OG, and DualShock 3 pressure-sensitive buttons, as well as Steam Deck and Steam Controller 2 pressure-sensitive touchpads. It converts these inputs to DirectInput axes, virtual DualShock 3 controllers, or the triggers and sticks of modern controllers. Modern controllers like the DualShock 4, DualSense, or the original Steam Controller (2015) feature a synthetic pressure-sensitivity option to assign touch inputs to predefined values (e.g., no touch: 0% press, touch: 50% press, and pressed touchpad: 100% press). The virtual DualShock 3 is natively recognized by the PCSX2 and RPCS3 emulators.
- [OpenController](https://github.com/Brunovncs/OpenController) - Supports DualShock 3 pressure-sensitive buttons. It assigns them to triggers - useful for racing games and shooters with multi-stage actions (aim vs shoot).
  
#### Premium
- [reWASD](https://rewasd.com) - Supports the DualShock 3, as well as the DualShock 2 via adapters that mimic a DS3. Pressure-sensitive buttons can be mapped to three distinct, staged zones, each activating a different action. It supports a virtual DualShock 3, which is compatible with RPCS3 and [older WX builds of PCSX2](https://github.com/PCSX2/pcsx2/releases/tag/v1.7.3771).

### Emulators
- PCSX2
- RPCS3
- DuckStation
- RetroArch

## Information
- [SDL3](https://github.com/libsdl-org/SDL/issues/5148) - native support for DualShock 3 pressure-sensitive buttons.

## Drivers
### DualShock 3
- [DsHidMini](https://github.com/nefarius/DsHidMini)
- [SCE Wireless Controller Driver v3.0.0.0](https://community.pcgamingwiki.com/files/file/2854-sce-wireless-controller-driver-v3000-official-drivers-for-dualshock-3/)
#### Retired
- [FireShock](https://github.com/nefarius/FireShock)
- [ScpToolkit](https://github.com/nefarius/ScpToolkit)
- [MotioninJoy](https://archive.org/details/motioninjoy-better-ds3)

### Xbox OG Controller
- [xbcd](https://github.com/thundercatsNZ/xbcd/releases)
- [Mayflash / TigerGame driver](https://www.s-config.com/xbcd-mayflash-xbox-joystick-driver/)

### DualShock 2
- [Bliss-Box_API_TOOL](https://sourceforge.net/projects/bliss-box-api/)

## License
[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
