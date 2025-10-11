# minui-map-txt-generator.pak

A MinUI pak wrapping [`minui-map-txt-creator`](https://github.com/josegonzalez/minui-map-txt-creator/) to generate map.txt files for Final Burn Neo romsets.

## Requirements

This pak is designed and tested on the following MinUI Platforms and devices:

- `miyoomini`: Miyoo Mini Plus (_not_ the Miyoo Mini)
- `my282`: Miyoo A30
- `my355`: Miyoo Flip
- `rg35xxplus`: RG-35XX Plus, RG-34XX, RG-35XX H, RG-35XX SP
- `tg5040`: Trimui Brick (formerly `tg3040`), Trimui Smart Pro

Use the correct platform for your device.

## Installation

1. Mount your MinUI SD card.
2. Download the latest release from Github. It will be named `Map.txt.Generator.pak.zip`.
3. Copy the zip file to `/Tools/$PLATFORM/Map.txt Generator.pak.zip`. Please ensure the new zip file name is `Map.txt Generator.pak.zip`, without a dot (`.`) between the words `txt` and `Generator`.
4. Extract the zip in place, then delete the zip file.
5. Confirm that there is a `/Tools/$PLATFORM/Map.txt Generator.pak/launch.sh` file on your SD card.
6. Unmount your SD Card and insert it into your MinUI device.

## Usage

> [!IMPORTANT]
> If the zip file was not extracted correctly, the pak may show up under `Tools > Map` or `Map.txt`. Rename the folder to `Map.txt Generator` to fix this.

Browse to `Tools > Map.txt Generator` and press `A` to enter the Pak.

### Debug Logging

Debug logs are written to the`$SDCARD_PATH/.userdata/$PLATFORM/logs/` folder.
