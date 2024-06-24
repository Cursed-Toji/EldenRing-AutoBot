# EldenRing-AutoFarm

<img src="https://i.postimg.cc/C50ft0Sp/Sacred-Relic-Sword.jpg" alt="Sacred Relic Sword" width="250">

This AutoHotkey script automates a series of actions in the game ELDEN RING™. When activated, it repeatedly executes a specific sequence of commands. This script is designed to be used at the "Estrada do Penhasco" bonfire and requires the Sacred Relic Sword for farming.

## Requirements

- [AutoHotkey](https://www.autohotkey.com/) installed on your system.
- "palace approach ledge road" bonfire in ELDEN RING™.
- Sacred Relic Sword.

## Installation

1. Ensure you have AutoHotkey installed. If not, download and install it from the [official website](https://www.autohotkey.com/).
2. Download this script and save it with the `.ahk` extension (e.g., `elden_ring_script.ahk`).
3. Double-click the `.ahk` file to start the script.

### Alternative: Compile to .exe

If the script does not work by double-clicking the `.ahk` file, you can compile the script to an executable:

1. Open AutoHotkey.
2. Go to the `Compile Script` menu.
3. Select the path to the `.ahk` file.
4. Save the file as an executable `.exe`.
5. Use the `.exe` file to run the script.

## How to Use

1. Open ELDEN RING™ and go to the "palace approach ledge road" bonfire.
2. Ensure you have the Sacred Relic Sword equipped.
3. Run the script by double-clicking the `.ahk` file or the `.exe` file you compiled.
4. Press `F3` to start the macro.
5. Press `F8` to reload the script.

## Script Details

The script is configured to:

- Set the working directory to the script's directory.
- Configure mouse coordinates mode to the active window.
- Force a single instance of the script to avoid multiple simultaneous executions.
- Set minimal delays for various commands to optimize speed.

### Sequence of Actions

1. Activates the ELDEN RING™ game window.
2. Repeats a sequence of commands:
   - Presses and releases `g` with specific intervals.
   - Presses and releases `f` with specific intervals.
   - Presses and releases `e` with specific intervals.
   - Presses and releases `j` with specific intervals (special weapon skill).
   - Presses and releases `w` with specific intervals.
   - Presses and releases `q` with specific intervals.

## Notes

- This script was created for automating specific tasks in the game ELDEN RING™ and may not be applicable to other situations.
- Use this script at your own risk. The use of macros and automation can violate the terms of service of some games, resulting in bans or other penalties.
- The key `J` is mapped to the special skill of the weapon.

## Contributions

Feel free to modify this script as needed. If you have improvements or suggestions, contribute with pull requests or open an issue in the repository.
