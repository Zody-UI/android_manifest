# ZodyUI
> No kangs, no fights.

ZodyUI is a custom Android ROM focused on UI/UX design and Chinese localization, based on [Android Open Source Project](https://source.android.com/).

## Syncing
`repo init -u https://github.com/Zody-UI/android_manifest.git -b sense`

> To make a shallow clone, please run:  
`repo init -u https://github.com/Zody-UI/android_manifest.git -b sense --depth=1`

`repo sync [-j8 --force-sync --no-clone-bundle --optimized-fetch --fail-fast --no-tags]`

## Building
`source build/envsetup.sh`  
`mka zody [-j8]`
