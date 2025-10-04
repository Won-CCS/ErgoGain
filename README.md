# ErgoGain

## Hardware
- See `kicad/` (schematics, PCB, BOM, gerbers)

## Firmware (QMK)
This repo uses a submodule for firmware:
- Repo: https://github.com/Won-CCS/qmk_firmware
- Locked commit: `77456cc`

### Build
```bash
git clone https://github.com/Won-CCS/ErgoGain.git
cd ErgoGain
git submodule update --init --recursive

cd firmware
qmk compile -kb ergogain -km default