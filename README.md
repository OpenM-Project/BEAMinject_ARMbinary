# Prebuilt ARM64 binaries for BEAMinject

## :question: Why this repository exists
GitHub Actions has no Windows ARM64 runner at the moment, so we cannot use the YML to build anything.

There are some ARM runners available, but they're in private beta and until there's Windows ones, we won't be switching (as it requires extra work).

## :inbox_tray: Downloads
- [**BEAMinject_ARM:**](https://github.com/OpenM-Project/BEAMinject_ARMbinary/raw/main/BEAMinject_ARM.exe)
Used for silently launching Minecraft then exiting
    - Recommended for most users
- [**BEAMinject_ARM_GUI:**](https://github.com/OpenM-Project/BEAMinject_ARMbinary/raw/main/BEAMinject_ARM_GUI.exe)
GUI version, mostly used for debugging etc.
    - Includes toggles for launching Minecraft, displays injection logs

We recommend trying BEAMinject first, and if you have issues, you can move to the GUI version for debugging.
