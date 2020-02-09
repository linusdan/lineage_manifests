# Lineage Manifests
Build Lineage 17.x for i9100 with rINanDO's repository (Alpha)

![lineage logo](https://github.com/linusdan/local_manifests/raw/lineage-17.x/lineage.png)


```
1. mkdir -p lineage-17

2. cd lineage-17

3. Initialize your local repository using the Lineage trees, use a command
  repo init -u git://github.com/LineageOS/android.git -b lineage-17.1

4. Clone my repo:
  git clone https://github.com/linusdan/lineage_manifests.git -b lineage-17.x .repo/local_manifests

5. Sync the repo:
  repo sync --no-tags --no-clone-bundle --force-sync -c

6. To build:
  . build/envsetup.sh
  lunch lineage_i9100-userdebug
  brunch i9100
```


Credits
-------
* [**rINanDO**](https://github.com/rINanDO)
* [**LineageOS**](https://github.com/LineageOS)
