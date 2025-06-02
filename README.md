# Akaneia Build

The Akaneia (/a.ka.ne.i.a/) build enhances Super Smash Bros. Melee by adding new fighters, stages, music, trophies, game modes, and much more—while keeping all the original content intact.

*Powered by the [m-ex](https://github.com/akaneia/m-ex) system.*

## Getting Started

### Patching the ISO 

To apply the Akaneia build patch, you will first need a clean *Super Smash Bros. Melee v1.2* ISO (MD5: `0e63d4223b01d9aba596259dc155a174`). 

You can download the latest patch release from:  
https://github.com/akaneia/akaneia-build/releases  

Detailed instructions for applying the patch are included in the release. 

Once patched, your ISO should match the
v1.0.0 (MD5:`8252729b0d37999fcb39534f68010d80`)

---

### Building the Project

This repository contains the project data for the latest version of the Akaneia build.

> **Note:** If you wish to build on top of this project, you will need to extract the files from the patched ISO yourself. 
> 
> Follow the steps below to get started.

#### 1. Clone Repository

#### 2. Get Akaneia Build ISO

1. See *Patching the ISO* for details on patching your iso.
2. Add iso location to dolphin game paths so that it appears in the game list.

#### 3. Extract Files Using Dolphin

1. Open **Dolphin** and locate the **Akaneia Build** entry in your game list.
2. Right-click the game and select **Properties**.
3. Go to the **Filesystem** tab.
4. Right-click on **Disc** in the file tree and choose **"Extract Entire Disc..."**
5. Choose the **"akaneia-build"** as the destination.

After extraction, your project folder should look like this:

```
akaneia-build/
├── assets/
├── data/
├── files/
├── sys/
└── akaneia.mexproj
```

#### 4. Open the Project in MexManager

1. Download MexManager from: https://github.com/Ploaj/MexManager/releases
2. Extract the archive and launch `MexManager.Desktop.exe`
3. Go to **File → Open** and select the `akaneia.mexproj` file
4. Make your desired edits (for more information see Cjag's [Guide to Melee Modding 1](https://docs.google.com/document/d/182_TA9ImYDFKohjvdautMTTK66k-mUaMmBP6Lt5FLhI/edit?tab=t.0))
5. Save your changes via **File → Save**
6. When ready, you may export the modified ISO using **File → Export ISO**
