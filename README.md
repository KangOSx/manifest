# KangOSx #

### Sync ###

```bash

# Initialize local repository
repo init -u https://github.com/KangOSx/manifest -b pie

# Sync
repo sync -c -j32 --force-sync --no-clone-bundle --no-tags
```

### Build ###

```bash

# Set up environment
$ . build/envsetup.sh

# Choose a target
$ lunch aosp_$device-userdebug

# Build the code
$ mka bacon -jX
```

### Submitting Patches ###

No patches are accepted

