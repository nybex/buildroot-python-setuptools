Setuptools 0.9.8 for buildroot

## Installation
```bash
$ cd $YOUR_BUILDROOT_DIR
$ rm -rf package/python-setuptools # Remove version that ships w/ buildroot
$ git clone https://github.com/nybex/buildroot-python-setuptools.git package/python-setuptools
$ echo 'source "package/python-setuptools/Config.in"' >> Config.in
$ make menuconfig # Select python-setuptools on the first screen
```
