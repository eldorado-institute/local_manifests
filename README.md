# local_manifests
Eldorado Research Institute AOSP Entry-Point

# Download Android source with local_manifests
 Refer to http://source.android.com/source/downloading.html

 $ repo init -u https://android.googlesource.com/platform/manifest -b android-14.0.0_r45
 $ git clone https://github.com/eldorado-institute/local_manifests .repo/local_manifests -b aosp-14
 $ repo sync

# Build for BananaPi F3
  https://github.com/eldorado-institute/device_bpif3
