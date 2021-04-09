# Lineage Manifests for i9100 #

### Sync ###

```bash
# Create build folder
$ mkdir -p lineage-18.1 && cd lineage-18.1

# Initialize local repository
$ repo init -u git://github.com/LineageOS/android.git -b lineage-18.1

# Clone my local repo
$ git clone https://github.com/linusdan/lineage_manifests.git -b lineage-18.x .repo/local_manifests

# Sync
$ repo sync -c --force-sync --no-clone-bundle --no-tags
```

### Build ###

```bash
# Set up environment
 $ . build/envsetup.sh

# Generate configuration of device
 $ lunch lineage_i9100-userdebug

# Build the code
 $ brunch i9100
 ```

Credits
-------
* [**rINanDO**](https://github.com/rINanDO)
* [**LineageOS**](https://github.com/LineageOS)
