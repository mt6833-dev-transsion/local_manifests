# how to use
```bash
# make folder
mkdir -p .repo/local_manifests

# curl
curl -L https://raw.githubusercontent.com/mt6833-dev-transsion/local_manifests/refs/heads/main/local_manifest.xml > .repo/local_manifests/mt6833_manifest.xml

# sync
repo sync -c --force-sync --no-clone-bundle --no-tags
