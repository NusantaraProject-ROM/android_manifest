### Corvus ROM ###

![CorvusROM](https://raw.githubusercontent.com/Rafiester/Public_Stuff/master/corvus_home.png)
<p align="center">

# Initialize Local Repository #
```bash
repo init -u https://github.com/Corvus-Project/android_manifest.git -b 10
```

# Syncing Repository # 
```bash
repo sync -j$(nproc --all) --force-sync --no-tags --no-clone-bundle
```

# Building Environment #
```bash   
# Set up environment
. build/envsetup.sh

# Choose a target
lunch du_device-userdebug

# Build the ROM
make corvus
```

 Credits:
 =======

 * [**DirtyUnicorns**](https://github.com/DirtyUnicorns)
