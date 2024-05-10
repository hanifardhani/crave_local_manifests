
## Local Manifests to build LineageOS for MI 8 Lite using CraveDevspace
### Usage

```bash
crave run --no-patch -- "rm -rf .repo/local_manifests && \
git clone https://github.com/hanifardhani/crave_local_manifests.git -b lineage-21.0 .repo/local_manifests && \
/opt/crave/resync.sh && \
source build/envsetup.sh && \
lunch lineage_platina-ap1a-userdebug && \
m bacon"
```

### Reference
[Crave Devspace](https://opendroid.pugzarecute.com/wiki/Crave_Devspace)
