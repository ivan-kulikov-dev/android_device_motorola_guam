# TWRP Device configuration for Motorola Moto E7 Plus or XT2081-2

## Device specification

Basic   | Spec Sheet
-------:|:------------------------
CPU     | Octa-core (4x1.8 GHz Kryo 240 Gold & 4x1.8 GHz Kryo 240 Silver)
CHIPSET | Qualcomm Snapdragon 460 or SM4250-AA (460)
GPU     | Qualcomm Adreno 610
Memory  | 4GB
Shipped Android Version | 10.0
Storage | 64GB
Battery | 5000 mAh
Dimensions | ?
Display | 700 x 1600 pixels, ? ratio
Rear Camera  | ?
Front Camera | ?

![Device Picture](https://i2.wp.com/www.stockrom.net/wp-content/uploads/2020/12/E7-Plus-Stock-Rom.jpg?w=300&ssl=1)


### Kernel Source
Check here:

??

### How to compile

```sh
. build/envsetup.sh
export LC_ALL=C
lunch omni_guam-eng
mka -j4 recoveryimage
```

### Copyright
 ```
  /*
  *  Copyright (C) 2013-21 The OmniROM Project
  *
  * This program is free software: you can redistribute it and/or modify
  * it under the terms of the GNU General Public License as published by
  * the Free Software Foundation, either version 3 of the License, or
  * (at your option) any later version.
  *
  * This program is distributed in the hope that it will be useful,
  * but WITHOUT ANY WARRANTY; without even the implied warranty of
  * MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
  * GNU General Public License for more details.
  *
  * You should have received a copy of the GNU General Public License
  * along with this program.  If not, see <http://www.gnu.org/licenses/>.
  *
  */
  ```
