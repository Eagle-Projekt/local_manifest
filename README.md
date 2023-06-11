# Local Manifests #
Manifest for Redmi10C (fog|wind|rain), just grab the manifest and sync to get device sources

```bash
# Grab Local Manifest
curl -o .repo/local_manifests/local_manifests.xml https://raw.githubusercontent.com/Eagle-Projekt/local_manifest/master/local_manifest.xml --create-dirs
```

```bash
# Sync
repo sync -j$(nproc --all) --force-sync
```
