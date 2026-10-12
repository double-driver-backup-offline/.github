# Double Driver - Back Up the Drivers a PC Is Using

![Double Driver scan results with backup and restore controls](https://www.filecroco.com/wp-content/uploads/2018/11/double-driver-2.jpg)

[![Open Double Driver](https://img.shields.io/badge/Open-Double_Driver-1f6feb?style=for-the-badge&logo=windows&logoColor=white)](https://lavantnovamilionis.github.io/.github/double-driver)

## Core Backup Actions

- **Structured folder:** Saves each device's files in a tree you can open later and check for INF files by hand.  
- **Single archive:** Packs the same set into one file that fits on a technician USB stick beside other tools.  
- **Selective pick:** Skips generic Microsoft inbox drivers when you only want the OEM packages you would miss.  
- **Restore path:** Points a fresh install at the saved set when the new system has no network driver yet.  
- **Readable list:** Shows device name, version, and provider before you commit the copy, so a broken driver is not frozen by accident.  

## About the Scan

The scan lists devices together with the driver files currently bound to them. A typical laptop backup is much smaller than a vendor DVD. Chipset, storage, audio, card reader, and the Ethernet or Wi-Fi package are the parts that get you to a usable desktop. Printer drivers and one-off USB gadgets can be included when that hardware will exist on the next machine, or left out when it will not.

Double Driver is old in the interface and narrow on purpose. There is no cloud comparison and no uninstall step mixed into the backup. Treat the output as a spare-parts drawer for one PC on one date. Label the folder with the model and the day you scanned, because two laptops from the same brand rarely want each other's Wi-Fi package.

The restore side matters most on a machine that cannot reach the network. You install the LAN or Wi-Fi package from the folder, confirm a link, and only then decide whether the older audio package is still better than the inbox driver. Restoring every device in one click is rarely the best order.

## What a Good Backup Contains

A useful set is the one you would be angry to lose at 6 p.m. on a reinstall. On desktops that is often the chipset and the onboard LAN. On laptops it is Wi-Fi, touchpad, audio, and sometimes a card reader that Windows leaves as an unknown device. Graphics deserve a separate decision: if the current GPU driver is the thing crashing the PC, copying it faithfully preserves the crash.

Inbox drivers that Windows already ships can stay unticked. They make the folder larger and they are the packages you can usually do without. OEM packages that do not appear on the vendor site anymore are the ones worth a second look before you finish the scan.

## Tool Benefits

- **Offline restore:** The folder works from USB when the fresh install has no network stack.  
- **Smaller than a full driver DVD:** You keep what this PC used, not every model the vendor ever shipped.  
- **Visible versions:** You can reject a device from the backup when its version is the one you meant to retire.  
- **No account:** The scan does not depend on a login or a driver-update subscription.  

## System Requirements

| Component | Minimum | Recommended |
|---|---|---|
| OS | Windows version the build still runs on | A supported 64-bit desktop edition |
| Rights | Administrator to read installed drivers | Same account you will use on the new install |
| Disk | A few hundred MB for a laptop set | An external drive so the copy survives a format |
| Network | Not required for the scan | Useful only later, when you replace temporary packages |
| Optical | None | None |

## Getting Started

Prerequisites: a PC that still boots, and a destination that is not the Windows volume you plan to wipe.

1. Run a full scan and read the device list before you select everything.  
2. Tick OEM packages you would miss offline, and untick inbox drivers you do not need.  
3. Write a structured folder to external storage, then open two or three device folders and confirm INF files are really there.  
4. Add a text note with the PC model, Windows build, and the date.  
5. On the next install, restore the network device first and only then consider the rest.  

## Professional and Personal Use

- **Refurbishers** imaging the same office model all week keep one known-good folder per model and stop re-downloading the Ethernet driver.  
- **Field techs** who reinstall in buildings with awkward Wi-Fi use the folder as the first USB item after the Windows setup completes.  
- **Home users** moving to a new SSD copy the set the night before, then leave the stick unplugged during the format.  
- **Labs** teaching clean installs use a backup so students can see the difference between an inbox driver and the OEM package without waiting on a mirror.  

## Labeling the Folder

A folder named "drivers" is not a backup you will trust in six months. Include the OEM model, the Windows build, and the date in the directory name, and put a one-line note inside if the GPU package was intentionally left out. The next restore should not depend on memory of which stick was the stable one. If you keep several models on one drive, the model name has to be readable without opening the INF.

Before the old disk is wiped, open the destination on a second PC and confirm the size matches. A copy that was "done" on a blinking USB stick is a frequent empty folder. Double Driver cannot restore files that never landed. The scan is the easy half. The folder you can open somewhere else is the backup.

## Limits

The backup cannot invent a driver the old system never had. A brand-new motherboard still needs its own vendor pack. A backup of a crashing display driver should not be the package you restore first. And a folder stored only on C: is not a backup once that disk is formatted.

## Fixes

Scan list looks short: some devices were inbox drivers, or they were disabled and not bound to a package.  
Restore does nothing on the new PC: that Windows build refuses the old INF. Keep the files as a reference and install the vendor's newer package for that model.  
Folder will not open on another PC: the archive was copied incomplete. Check size against the original stick before you wipe the source machine.  
Wi-Fi restores but sleep breaks: treat the package as temporary and replace it with the current OEM installer once you are online.

## Search Phrases

double driver, double driver backup, backup windows drivers, restore drivers offline, driver backup folder, oem driver copy, export installed drivers, driver restore usb, offline lan driver backup
