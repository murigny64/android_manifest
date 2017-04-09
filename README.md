AOSP for Moto G4 Plus (Athene)
===========

Getting Started
---------------

To get started with Android, you'll need to get
familiar with [Git and Repo](http://source.android.com/source/using-repo.html).

To initialize your local repository using the CAF AOSP trees, use a command like this:

```repo init -u https://github.com/Nougat-Athene/android_manifest.git -b nougat-7.1```

Then to sync up:

```repo sync -f -c --force-sync -j64 --no-tags --no-clone-bundle```
