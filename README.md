## Repo


```
 repo sync  -f --force-sync --no-clone-bundle --no-tags -j$(nproc --all)
```
###  Copy roomservice to
```
.repo/local_manifests/local_manifests.xml
```

### Compiling Source

Set up environment:
```
source build/envsetup.sh

add_lunch_combo potato_dumpling-userdebug

brunch dumpling
```
