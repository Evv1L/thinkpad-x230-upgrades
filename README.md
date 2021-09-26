![](https://i.redd.it/qr5igeglrmz01.png "0pk")
# Thinkpad X230 upgrades
This repo is a list of upgrades for ThinkPad X230 I found around the internet. Some of this upgrades I made personally<br>

## Screen
### Stock screens
### Mods
#### 12.5" inch
#### 13.3" inch
#### 19:10 aspect ratio screen

## Motherboard (CPUs)
### Stock CPUs
### Custom BGA CPUs

## Fan & heatsink
**Don't buy new fans without a hetsink**, otherwise they will be not compailable.
### Delta fan
### Toshiba fan
### AVC fan
AVC fan is best for cooling.

## BIOS mods
### EC patch
### 1vyrain bios
### Coreboot

## Battery
Biggest battery you can get is 9 cell 8400 mAh battery.
Also you can use 9 cell battery as a handler.

## SATA slot
Any 2.5 SATA III SSD works.<br>
2.5 HDDs is hard to fit.

## RAM
Motherboard supports 16 Gb kit 2133 Mhz (or even 2400 Mhz) DDR3L memory.
Some people reported froblems with HyperX RAM (dont boot up)

## Keyboard
Keyboards you can install:
- Stock 30-series keyboard non-backlit
- Stock 30-series keyboard backlit
- 20-series keyboard (need EC flash and pin mod)
You can also use keyboards from T and W series.

## Trackpoint
> Custom trackpoints exists, but I have no info about them.

## Palm rest
**Avoid non original palm rest**. At least I had non original and it was a bit bigger, bad plastic and no ducts for fluid drainage.

Palm rests variants:
- Normal palm rest
- Palm rest with a fingerprint reader
Also you can place 2nd mSATA under palmrest if you have a.gain board and palm rest without fingerprint.

## Speakers
You can install MacBook speakers

## Wifi (PCI-e)
There is a whitelist for WIFI cards, but you can remove it with 1vyrain.
### Before 1vyrain
### After 1vyrain
AX210NGW with M.2 to mSATA adapter

## External antenna
You need to drill 1/4 inch hole for antenna.

## WWAN slot (mSATA)
### SSDs
All mSATA are compailable without any BIOS mods, **but** mSATA works with **SATA II**
 speeds (hardware limitation) and these SSDs are not common already.
### WWANs
There is a whitelish for WWAN cards, but you can remove it with 1vyrain.
#### Before 1vyrain.
Only 3G WWAN modules
#### After 1vyrain
> Need more info about 4G WWAN cards
 
## Bluetooth
You can replace Bluetooth module with a USB for wireless mouses.
If you want to upgrade Bluetooth buy a newer WIFI card (like AX210NGW). They have Bluetooth build in. After that you can remove or disable your stock Bluetooth module.

## Power
Default for X230 is 90W power adapter.
Also you can replace DC charging connector with a Type-C connector.

## Docks
> TODO: Is Ultrabase uses SATA III?
There are 2 docks for X230 that I personally owned:
- ThinkPad **Ultrabase** Series 3
- ThinkPad Mini Dock Plus Series 3 with USB 3.0 (**4338**)

**Ultrabase** have a SATA III slot for HDD/SSD or CD drives, DisplayPort, 4xUSB 2.0, VGA, Microphone jack, Headphone jack.
**Mini Dock (4338)** have USB 3.0, 2xDisplayPort, 6xUSB 2.0, VGA, Microphone jack, Headphone jack.

Linux doesn't detect drive from UltraBase dock after sleep and reattach. Mini Dock 4338 doesn't have this problem, because it uses USB intead of SATA to connect drives.
You can use Ultrabase dock for booting or installing Windows because of SATA interface.

## ExpressCard 54 slot
There are ExpressCards you can install:
### Smartcard reader
If you really want it.
### 2xUSB 3.0 adapter
**Buy adapter with ASM1042 controller**, otherwise your adapter will have heating problems.
### 3xUSB 3.0 adapter
I don't recomend it because of limited space and overheating, but you still can install it.
### ExpressCard to M.2 2242 NVMe adapter (and USB 3.0)
In short, sequential reads/writes may not be faster than a good SATA SSD but random 4K reads/writes are significantly faster due to the faster protocol. Even dram-less SSD is marginally faster than SATA.
Also M.2 with USB 3.0 port are available.
### WIFI and in ExpressCard
> Need more info from xyte.ch
### External Graphics Card (eGPU)
750Ti and external screen is recomended due to limited bandwith of ExpressCard

## Camera
> I don't know any camera mods. Maybe you know? :)

## ThinkLight
> I saw many red and yellow thinklights, but I don't know how they did this.

## LED board
> I don't know any LED board mods. Maybe you know? :)

## Software
### thinkfan (linux)
Create custom profiles for your fan to reduce temps
