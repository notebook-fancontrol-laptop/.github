# NoteBook FanControl - A Laptop Fan Config for This Model

![NoteBook FanControl with a model-specific config enabled](https://i.ytimg.com/vi/3BiMA8Bb2Cc/sddefault.jpg)

## At a Glance

Desktop fan tools talk to motherboard headers. Many laptops ignore them. NoteBook FanControl talks to the embedded controller using a per-model config. The config is the product as much as the program. Load the one that matches the board, set a curve or a fixed speed you can observe, and watch temperatures in another tool. A silent fan and a climbing CPU means the config did not take. Go back to automatic before you cook the machine.

- A config for this exact laptop
- A short manual test so you hear the fan
- Temperatures watched somewhere else
- Automatic mode still available
- No random config from a similar-looking model

1. Find the config that names your model.
2. Enable it and set a moderate speed.
3. Confirm the fan changes.
4. Run a short load and read the CPU temperature.
5. If the fan stays still, disable the program and use the laptop's own control.

## Fits

A supported laptop whose BIOS fan behavior you want to override carefully. A poor fit for a desktop. A poor fit when your model has no config. A poor fit for a fan that is mechanically dead. Software will not free a stuck rotor.

[![Open NoteBook FanControl](https://img.shields.io/badge/Open-NoteBook_FanControl-1d4ed8?style=for-the-badge&logo=windows&logoColor=white)](https://novabutkusxndtnd.github.io/.github/notebook-fancontrol-laptop)

## Requirements

| Item | Expectation |
|---|---|
| Laptop | A listed model |
| Config | That model's file |
| Test | You can hear or see the fan |
| Exit | Automatic mode if the test fails |

## Fixes

No config matches. Do not load a cousin model.
The fan does not respond. Disable NoteBook FanControl. The EC is not the one the file expects.
Temperatures rise and the fan stays at your low fixed speed. Raise the curve or return to automatic.
Two fan tools are installed. Keep one.
The change vanishes at sleep. Confirm the service is allowed to start, after the curve is proven.

## A Config You Can Hear

NoteBook FanControl only works when the config matches this laptop's embedded controller. A file for a similar model can sit on screen and never move the fan. Load the named config, set a moderate speed, and listen. If nothing changes, turn the program off and let the BIOS run the fan. A silent fan plus a rising CPU is not a successful curve.

Watch temperature in another tool while you test. This program sets speed. It does not prove the cooler is adequate. A fixed low speed during a render will overheat a machine that was fine on automatic. Raise the curve or go back. Do not leave two fan utilities installed. The second one will overwrite the first at the next boot.

| Test | What you learn |
|---|---|
| Manual speed, fan changes | The config matches |
| Manual speed, silence | Wrong model file |
| Load, temperature climbs, fan stays low | Curve is too weak |
| Two tools installed | Keep one |

Name the profile after the laptop, not "default." After a BIOS update, test again. Firmware sometimes takes the fan back and the old config no longer applies.

## Hear the Fan or Turn It Off

The config file is the product. NoteBook FanControl without a match for this exact laptop should not be left running. Set a moderate manual speed. If you cannot hear or see the fan change, disable the program and return the machine to the BIOS curve. A wrong config that "applies" and does nothing is how a CPU overheats while the window looks fine.

Watch temperatures elsewhere during a short render. If the fan stays at the low number you chose while the CPU climbs, the curve is too weak. Raise it or go back to automatic. Do not install a second fan utility beside it. After a BIOS update, test the fan again. Firmware can take control back.

- Config name matches the laptop
- Manual test you can hear
- Temperature watched in another tool
- Automatic mode still available
- One fan program, not two

A seized fan will not start because the curve asked. That is hardware.

## Reader Terms

notebook fancontrol, nbfc laptop fan, notebook fancontrol config, laptop fan curve, embedded controller fan, nbfc model config, laptop fan automatic, notebook fancontrol windows
