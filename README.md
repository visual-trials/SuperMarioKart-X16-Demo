# Generate files

To generate mario files run this script from the root folder:

```python utils/extract_tiles_and_tilemap.py```

This will generate files in the SD/TBL folder.

To generate FX perpective table files run this script from the root foldeR:

```python utils/generate_mode7_tables.py```

This will generate files in the SD/TBL folder.

# Build
To build a PRG file run this from the root folder:

```cl65 -t cx16 -o SD/SUPER-MARIO-KART.PRG super_mario_kart.s```

This will generate a PRG in the SD folder.

# Run using the emulator
To run using the emulator go to the SD folder and run this:

```x16emu.exe -prg SUPER-MARIO-KART.PRG -run```

# Run on real hardware

To run on real hardware, copy the contents of the SD folder into a folder on your SD card and load/run SUPER-MARIO-KART.PRG

# Screenshot

![Super Mario Kart demo](assets/demo_screenshot.png?raw=true "Super Mario Kart demo")


