<p align="center">
<img src="https://github.com/ColtOS/manifest/raw/cos7.x/colt_logo.png" > 
</p>

Colt-OS Project
===============
ColtOS Project is a team of learners and based on lineageos with some customizations.
We have cherry-picked the features from many 
other roms/projects and we are very thankfull to them!!


-------
* [**LineageOS/Cyanogenmod**](https://github.com/LineageOS)
* [**crDroid**](https://github.com/crdroidandroid)
* [**DirtyUnicorns**](https://github.com/DirtyUnicorns)
* [**AOSiP**](https://github.com/AOSIP)
* [**TeamSubstratum (Theme Engine)**](https://github.com/Substratum)
* [**Pure Nexus**](https://github.com/PureNexusProject)


How to Build?
-------------

To initialize your local repository using the ColtOS trees, use a 
command like this:

```bash
  repo init -u git://github.com/ColtOS/manifest.git -b cos7.x
```
  
Then to sync up:
----------------

```bash
  repo sync
```
Finally to build:
-----------------

```bash
  . build/envsetup.sh
  brunch <device_name>
```

