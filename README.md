# Prebuilt ARM64 binaries for BEAMinject

## :question: Why this repository exists
GitHub Actions has no Windows ARM64 runner at the moment, so we cannot use the YML to build anything.

Until Windows ARM64 runners are available to any workflows, this will stay here and be updated with every build.

## :inbox_tray: Downloads
- [**BEAMinject_ARM:**](https://github.com/OpenM-Project/BEAMinject_ARMbinary/raw/main/BEAMinject_ARM.exe)
Used for silently launching Minecraft then exiting
    - Recommended for most users
- [**BEAMinject_ARM_GUI:**](https://github.com/OpenM-Project/BEAMinject_ARMbinary/raw/main/BEAMinject_ARM_GUI.exe)
GUI version, mostly used for debugging etc.
    - Includes toggles for launching Minecraft, displays injection logs

We recommend trying BEAMinject first, and if you have issues, you can move to the GUI version for debugging.
