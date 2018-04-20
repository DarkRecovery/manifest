
**Dark Recovery Project**


Credits
=======
* [**Teamwin Recovery Project (Base)**](https://github.com/TeamWin)
* [**Omnirom**](https://github.com/omnirom)
* [**RedWolf TWRP**](https://github.com/RedWolfRecovery)
* [**PitchBlack TWRP**](https://github.com/PitchBlackTWRP)


Getting Started
===============

To get started with OMNI sources to build TWRP, you'll need to get
familiar with [Git and Repo](https://source.android.com/source/using-repo.html).

To initialize your local repository using the OMNIROM trees to build TWRP, use a command like this:
```bash
    repo init -u git://github.com/DarkRecovery/dr_manifest.git -b dr
```
Then to sync up:
```bash
repo sync
```

 Compilation Of Dark Recovery
=============================
 
```bash
     cd <source-dir>
     . build/envsetup.sh
     lunch omni_<device>-eng
     mka recoveryimage
```

