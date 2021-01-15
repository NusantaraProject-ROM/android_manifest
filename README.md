# Initialize Local Repository #
```bash
repo init -u ssh://git@github.com/Nusantara-ROM/android.git -b 10

# else if you want to sync with specific tags (this also specific features inline with selected tag version)

repo init -u ssh://git@github.com/Nusantara-ROM/android.git -b refs/tags/<tags>
```

# Syncing Repository # 
```bash
repo sync -j$(nproc --all) --force-sync --no-tags --no-clone-bundle
```

# Lunch Command # 
```bash
. build/envsetup.sh

lunch nad_$device-userdebug

mka nad -j
```
