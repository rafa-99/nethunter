# Kali Linux Nethunter

Kali Linux Nethunter Install Script for Android without the requirement of a modified kernel and a TWRP recovery.

![alt-text](https://gitlab.com/kalilinux/nethunter/build-scripts/kali-nethunter-project/raw/master/images/nethunter-git-logo.png)

## Disclaimer and Warning

I am not responsible for bricked devices, dead SD cards, thermonuclear war,
or you getting fired because the alarm app failed.
Please do some research if you have any concerns about features included
in the products you find here before flashing it!
YOU are choosing to make these modifications.

I'm not responsible if you do any damage to your device
I'm not responsible if your device ends up in a brick state
You take full responsibility of everything in this, so please be careful!

This software is for educational purposes only and must only be used in allowed environments.

## Requirements

* Rooted Android Phone;
* Minimal Knowledge of how the terminal and the unix environment works.

## Installation

1. Download and unzip the script folder anywhere on your sdcard/internal memory;
2. Open-up a android terminal (You can use [Terminal Emulator](https://play.google.com/store/apps/details?id=jackpal.androidterm)) and type `su`;
3. After logging in as root, navigate to the folder where you extracted the script folder and type `sh nethunter`
4. The script will start running, and then just simply wait until the installation process is finished to open up the nethunter app and install Chroot;

## FAQ's

Q: Is this script compatible with any phone?

A: The script is almost compatible with any rooted phone, either way, I'm opened up to receive new suggestions to improve the script.

Q: After running the script when I try to install Chroot I get a `ssl.excpection error`, what should I do?

A: Go [HERE](https://build.nethunter.com/kalifs/kalifs-latest/) and download the desired package ending up with the `.tar.xz` extension (I recommend downloading one of the armhf packages for compatibility purposes), and put the file in the root of your sdcard with this name `kalifs-[full/minimal].tar.xz`. After doing this, click on the manual install of chroot and choose the sdcard path.

Q: I can preform any apt operations, what about now?

A: Type this on the *kali terminal* `wget -q -O - https://archive.kali.org/archive-key.asc  | apt-key add`.

## Contributors

* [offensive-security](https://github.com/offensive-security)
* [Kali Linux](https://gitlab.com/kalilinux)
* [spyrotecher](https://github.com/spyrotecher)
* [Atarii](https://github.com/atarii)
* [antuketot76](https://github.com/antuketot76)
* [Gongas99](https://github.com/Gongas99)
