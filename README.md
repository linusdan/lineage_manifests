# Lineage Manifests
Build Lineage 16.0 for i9100 with rINanDO's repository (Only for tests)

![lineage logo](https://github.com/linusdan/local_manifests/raw/lineage-16.0/lineage.png)


```
1. mkdir -p lineage-16.0

2. cd lineage-16.0

3. Initialize your local repository using the Lineage trees, use a command
  repo init -u git://github.com/LineageOS/android.git -b lineage-16.0

4. Clone my repo:
  git clone https://github.com/linusdan/lineage_manifests.git -b lineage-16.0 .repo/local_manifests

5. Sync the repo:
  repo sync --no-tags --no-clone-bundle --force-sync -c

6. Add vendorsetup.sh in device/samsung/i9100:
 cd device/samsung/i9100
 wget -c https://raw.githubusercontent.com/linusdan/lineage_manifests/lineage-16.0/vendorsetup.sh
 cd ../../..

7. To build:
  . build/envsetup.sh
  lunch (choose i9100)
  brunch i9100
```


Credits
-------
* [**rINanDO**](https://github.com/rINanDO)
* [**LineageOS**](https://github.com/LineageOS)
