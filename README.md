Courbet Android Building
===========

Getting started
---------------
Use command this to clone the local manifest at the root of your local repository:
```
git clone -b 17 https://github.com/Szes-Labs/courbet_manifest.git .repo/local_manifests
```
Then to sync up:
```
repo sync --no-clone-bundle --no-tags -j"$(nproc --all)"
```
