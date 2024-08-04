# Download Android source with local_manifests
 Refer to http://source.android.com/source/downloading.html
``` bash
 repo init -u https://android.googlesource.com/platform/manifest --depth=1 -b android-14.0.0_r37
 git clone https://github.com/yash3056/local_manifest.git .repo/local_manifests -b main
 repo sync
```
Use -j[n] option on sync & build steps, if build host has a good number of CPU cores.
