# rpilg-local_manifest
## Download Source
```
mkdir rpilg-16
cd rpilg-16
repo init -u git://github.com/LineageOS/android.git -b lineage-16.0
mkdir -p .repo/local_manifests
wget -O .repo/local_manifests/local_manifest.xml https://raw.githubusercontent.com/wayyoung/rpilg-local_manifest/lineage-16.0/manifest_brcm_rpi4.xml
repo sync
```
