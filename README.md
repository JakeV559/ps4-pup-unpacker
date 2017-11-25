# pup_unpacker
A utility to unpack PS4 update blobs that have been previously decrypted using [pup_decrypt](https://github.com/idc/ps4-pup_decrypt/). this is based on [idc](https://github.com/idc)/[ps4-pup_unpack](https://github.com/idc/ps4-pup_unpack) rewritten with C++ and runs on Linux/OSX/Win32

## Note
This utility will not unpack the contents of nested filesystems. The filesystem images in updates are FAT32, exFAT, etc images and can be mounted or unpacked with other tools.


## To Build
This app contains dependency to [mateidavid/zstr](https://github.com/mateidavid/zstr) as a submodule, as such it must be initiated before building.
to do so run the following command:
```
git submodule update --init
```
