# android_device_xiaomi_psyche-ofox
For building OFRP for Xiaomi Mi 12X

OrangeFox device tree for Xiaomi Mi 12X

The Xiaomi Mi 12X (codenamed _"psyche"_) is a mid range smartphones from Xiaomi.

## Device specifications

| Device       | Xiaomi Mi 12X                               |
| -----------: | :------------------------------------------ |
| SoC          | Qualcomm SM8250 Snapdragon 870 5G           |
| CPU          | 8x Qualcomm® Kryo™ 585 up to 2.84GHz        |
| GPU          | Adreno 650                                  |
| Memory       | 8GB / 6GB  (LPDDR 5)                        |
| Shipped Android version | 11                               |
| Storage      | 128GB  (UFS 3.1)                            |
| Battery      | Li-Po 4520 mAh, non-removable               |
| Dimensions   | 163.7 x 76.4 x 7.8 mm                       |
| Display      | 1080 x 2400 (20:9), 6.67 inches             |

## Device picture

![Xiaomi Mi 12X](https://fdn2.gsmarena.com/vv/pics/xiaomi/xiaomi-12x-2.jpg)

## Features

**Works**

- Booting.
- **Decryption** (Android 11)
- ADB
- MTP
- OTG
- vA/B partition functions
- Vibration

Mi 12X is using Virtual A/B Partition Scheme!

## Compile

You can find a full compile guide for OrangeFox [Here](https://wiki.orangefox.tech/en/dev/building)

Lunch command :
```
lunch twrp-psyche_eng && mka adbd bootimage
```



## Thanks
- [Original Tree By Nebrassy](https://github.com/TeamWin/android_device_xiaomi_alioth)
