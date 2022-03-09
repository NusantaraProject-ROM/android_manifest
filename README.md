# Initialize Local Repository #
```bash
repo init -u ssh://git@github.com/Nusantara-ROM/android_manifest.git -b 12.1

# else if you want to sync with specific tags (this also specific features inline with selected tag version)

repo init -u ssh://git@github.com/Nusantara-ROM/android_manifest.git -b refs/tags/<tags>
```

# Syncing Repository # 
```bash
repo sync --force-sync --no-tags --no-clone-bundle
```

# Lunch Command # 
```bash
mka nad -j
```
