## About
This is a fork of the original Kali "live-build-config" project located [here](http://git.kali.org/live-build-config.git)

The original repo has been added as an upstream remote to keep the project updated. Simply fetch and merge from `upstream/master`.

## Using / Compiling
The official Kali live build documentation can be [found here](https://docs.kali.org/development/live-build-a-custom-kali-iso) and should be used. Simply replace the git clone address with the address of this repo.

## Changing Desktop Environments
If you'd like to use an environment other than XFCE, simply copy `kali-config/variant-xfce/package-lists/kali.list.chroot` into the appropriate `kali-config/variant-*` folder and remove the xfce line from the chroot file.

