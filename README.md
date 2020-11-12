# AVD Devices

## Setup

### Skins

Copy Skins to Default Skin folder.

```bash
cp -R Skins/ $HOME/Library/Android/sdk/skins
```

If importing device this should work automatically. If not there seems to be a bug in mac where you have to create the device. Edit it to open the 3 dot menu folder navigator for the skin drop down, then you select the folder of the new Skin and hit Open.

### Import Hardware Profile


#### Samsung
* Galaxy A51
  * 6.5 inches (~87.4% screen-to-body ratio)
  * 1080 x 2400 pixels (~405 ppi density)
  * 4GB RAM
  * Galaxy A51 Skin
* Galaxy A50
  * 6.4 inches (~87.4% screen-to-body ratio)
  * 1080 x 2340 pixels (~403 ppi density)
  * 4GB RAM
  * Using Galaxy A51 Skin
* Galaxy S10
  * 6.1 inches (~88.3% screen-to-body ratio)
  * 1440 x 3040 pixels (~550 ppi density)
  * 8 GB RAM
  * Galaxy S10 Skin
* Galaxy S10
  * 6.1 inches (~88.3% screen-to-body ratio)
  * 1440 x 3040 pixels (~550 ppi density)
  * 8 GB RAM
  * Galaxy S10 Skin
* Galaxy S9+
  * 6.2 inches (~84.2% screen-to-body ratio
  * 1440 x 2960 pixels (~529 ppi density)
  * 6GB RAM
  * Galaxy 9+ Skin
* Galaxy S9
  * 6.2 inches (~84.2% screen-to-body ratio
  * 1440 x 2960 pixels (~529 ppi density)
  * 4GB RAM
  * Galaxy 9 Skin
* Galaxy S8+
  * 6.2 inches (~84.0% screen-to-body ratio)
  * 1440 x 2960 pixels (~529 ppi density)
  * 4 GB RAM
  * Galaxy 8+ Skin
* Galaxy S8
  * 5.8 inches (~83.6% screen-to-body ratio)
  * 1440 x 2960 pixels (~570 ppi density)
  * 4GB RAM
  * Galaxy 8 Skin
* Galaxy S7
  * 5.1 inches (~72.10% screen-to-body ratio)
  * 1440 x 2560 pixels (~577 ppi density)
  * 4GB RAM
  * Galaxy 7 Skin
  * Physical Buttons
* Galaxy S7e
  * 5.5 inches (~76.1% screen-to-body ratio)
  * 1440 x 2560 pixels (~534 ppi density)
  * 4GB RAM
  * Galaxy 7 Edge Skin
  * Physical Buttons


#### Huawei
Huawei P30 Pro
* P30 Pro
  * 6.47 inches, 102.8 cm2 (~88.6% screen-to-body ratio)
  * 1080 x 2340 pixels, 19.5:9 ratio (~398 ppi density)
  * 6GB RAM
* P30 Lite
  * 6.15 inches (~84.2% screen-to-body ratio)
  * 1080 x 2312 pixels (~415 ppi density)
  * 4GB RAM
* P20
  * 5.8 inches, 84.9 cm2 (~80.4% screen-to-body ratio)
  * 1080 x 2240 pixels, 18.7:9 ratio (~429 ppi density)
  * 4GB RAM
* P20 Lite
  * 5.84 inches, 85.1 cm2 (~80.5% screen-to-body ratio)
  * 1080 x 2280 pixels, 19:9 ratio (~432 ppi density)
  * 4GB RAM
* P20 Pro
  * 6.1 inches, 93.9 cm2 (~82.0% screen-to-body ratio)
  * 1080 x 2240 pixels, 18.7:9 ratio (~408 ppi density)
  * 6GB RAM
* P10
  * 5.1 inches, 71.7 cm2 (~71.2% screen-to-body ratio)
  * 1080 x 1920 pixels, 16:9 ratio (~432 ppi density)
  * 4GB RAM
* P10 Lite
  * 5.2 inches, 74.5 cm2 (~70.7% screen-to-body ratio)
  * 1080 x 1920 pixels, 16:9 ratio (~424 ppi density)
  * 3 GB

##### Caveats

You can see in the xml files the GiB Ram Size being set. It does save (you can check by exporting the profile) but whenever you open a profile to edit it will show the RAM size as 2048 or 1536 MB and if you save it will change the RAM Size.

## Resources
* [Galaxy Skins](https://developer.samsung.com/galaxy-emulator-skin/guide.html)
* Hardware specs generally from [GSM Arena](https://www.gsmarena.com/)
