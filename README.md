# Local Manifests #
Manifest for Redmi10C (fog|wind|rain), just grab the manifest and sync to get device sources

```bash
# Grab AOSP Manifest
curl -o .repo/local_manifests/local_manifests.xml https://raw.githubusercontent.com/Eagle-Projekt/local_manifest/master/aosp_manifest.xml --create-dirs
```

```bash
# Grab YAAP Manifest
curl -o .repo/local_manifests/local_manifests.xml https://raw.githubusercontent.com/Eagle-Projekt/local_manifest/master/yaap_manifest.xml --create-dirs
```


```bash
# Sync
repo sync -j$(nproc --all) --force-sync
```
