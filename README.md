Realme 8i/Narzo 50 Device Tree - spaced
================================================================

## Specifications

Basic   | Spec Sheet
-------:|:-------------------------
CPU     | Octa-core (2x2.05 GHz Cortex-A76 & 6x2.0 GHz Cortex-A55)
Chipset | MediaTek Helio G96 (12 nm)
GPU     | Mali-G57 MC2
Memory  | 4/6 GB
Shipped Android Version | Android 11, realme UI 2.0 
Storage | 64/128 GB (UFS 2.1)
MicroSD | Up to 512 GB 
Battery | Li-Po 5000 mAh, non-removable
Dimensions | 164.1 x 75.5 x 8.5 mm (6.46 x 2.97 x 0.33 in)
Display | 1080 x 2412 pixels, 6.6" IPS LCD 120 Hz, 20.1:9 ratio (~400 ppi density)
Rear Camera  | Triple : 50 MP; 2MP(depth); 2MP(macro)
Front Camera | Single: 16 MP

## Building TWRP

To build:

0. Setup envirnoment
```bash
. build/envsetup.sh
```

1. Then prepare
```bash
lunch twrp_spaced-eng
```

2. Finally, make the image
```bash
m recoveryimage
```

## Locate the built image
```bash
cd $OUT
```
see **recovery.img**

Copyright (C) 2021 Team Win Recovery Project
