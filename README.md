# Local_manifest
A local manifest needed for early a11 builds for X00P
to use this
git clone https://github.com/Flamefusion/local_manifest.git -b master .repo/local_manifests

repo sync -c --force-sync --no-tags --no-clone-bundle -j$(nproc --all) --optimized-fetch --prune
