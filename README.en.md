# Forza Horizon 2: PlayStation button prompts

[Português](README.md) · **English**

Replaces Forza Horizon 2's Xbox button icons with PlayStation ones (the Xbox One version running on the Azimuth emulator). It also swaps the controller diagram on the controls screen for a DualSense.

Nothing to install or run: just copy the files over the game's own.

![Icons](docs/icons.png)
![Help screen icons](docs/help_buttons.png)
![DualSense diagram](docs/diagram.png)

## What changes

- **Face buttons:** A → ✕, B → ○, X → □, Y → △, coloured as on PlayStation.
- **Bumpers and triggers:** LB/RB/LT/RT → L1/R1/L2/R2.
- **Sticks:** LS/RS → L/R, and stick clicks → L3/R3.
- **View → touchpad.**
- **Controls screen:** the controller drawing becomes a DualSense, and the callout lines point at the buttons where they sit on a DualSense.

The D-pad, Menu/Options and the steering wheel diagram stay as in the original.

## Installation

1. **Back up** these 5 game files so you can undo the change:
   - `Mount\media\UI.zip`
   - `Mount\media\zipmanifest.xml`
   - `Mount\media\ui\textures\data_bound\ControllerIcons.zip`
   - `Mount\media\ui\textures\data_bound\Help_Buttons.zip`
   - `Mount\media\ui\textures\data_bound\UI_Symbols.zip`
2. Download `fh2-dualsense-ui.zip` from the [latest release](https://github.com/Theiago/fh2-dualsense-ui/releases/latest).
3. Extract the zip into the game's `Mount` folder (`...\Forza Horizon 2\Mount\`). When Windows asks, choose **replace the files**.
4. Start the game.

Alternatively, without the zip: copy this repository's `Mount` folder into the game folder (the one with `Azimuth.exe`).

## Uninstalling

Put the 5 backed-up files back.

## Compatibility

- Made for the Forza Horizon 2 game files that run on Azimuth, with the Storm Island DLC.
- **The 5 files must be installed together.** `zipmanifest.xml` stores the internal position of each of the game's `.zip` files, and its values match the `.zip` files in this repository.
- **Not compatible with other mods that change these same 5 files.** A mod that replaces another of the game's `.zip` files and also updates `zipmanifest.xml` will conflict, because each one overwrites the other's manifest.

## Known issues

- If your copy of the game differs from the one used here, the game may reject the files or crash. In that case, restore your backup.
