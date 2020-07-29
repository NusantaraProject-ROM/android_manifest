# Initialize Local Repository #
```bash
repo init -u ssh://git@github.com/Nusantara-ROM/android.git -b 10
```

# Syncing Repository # 
```bash
repo sync -j$(nproc --all) --force-sync --no-tags --no-clone-bundle
```
