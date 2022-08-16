# <img src="https://github.com/KogasaKyokai/platform_manifest/blob/Tatara/Banner.png" width="300"> #

### What is this? ###

``KogasaKyokai`` is an open sourced Android Project founded by Touhou fans.

### To Sync ###

```bash
# Initialize local repository
$ repo init -u https://github.com/KogasaKyokai/platform_manifest -b Tatara

# Sync
$ repo sync -j4
```

### To Build ###

```bash
# Set up environment
$ . build/envsetup.sh

# Choose a target
$ lunch kogasa_$device-userdebug

# To build
$ make bacon -j$(nproc --all)
