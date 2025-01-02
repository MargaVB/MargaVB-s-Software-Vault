# MargaVB's Minion Masters Replays Manager

This is a **tool** for the game '**Minion Masters**' ( (C) ***BetaDwarf*** ).

## Directly Download *'MargaVB's Minion Masters Replays Manager **V0.50.3**'* from here:

* https://drive.google.com/uc?export=download&id=15hCu8Xmbpas0AJGRCu3Mx_9VHKEJeUS8

#### NOTE: The download from Google Drive may not be able to finish a virus scan properly. It only scans Documents, PDFs, and images, **not** '***.exe files***'. Here are the results from VirusTotal as an alternative:

* [MMReplayManager.exe] https://drive.google.com/uc?export=download&id=1iNHy_bNvPJ7ckbM_WgCDeJtlw3pjmnuX

* [Install Wizard] https://drive.google.com/uc?export=download&id=16RjP304bsl8yAguYtUvh8JDaK43ppmM0

    As you can see the ***'MargaVB's Minion Masters Replays Manager'*** **exe file** is **not flagged at all**.
    The ***Install Wizards File*** is being flagged by only two malware detectors which are both known for **flagging eveything** that has not been uploaded to their whitelisting database. Maybe they would like to charge developers for adding their software to the whitelist.

## Important: Every new version of the tool will be available via this README file on this Github repository

* https://github.com/MargaVB/MargaVB-s-Software-Vault

## Purpose
* select and delete replay files to reduce replay lists (the files are saved to backup folder(s))
* get overall statistics for all matches since first start of this tool (all time wins/losses, all time winratio)
* get statistics for a certain 'Master & Deck' combination of yours (wins/losses and winratio)
* get info about all replays: own/opponents's master, deck and rank at that time, all wins/losses and winratio with that deck
* mark a certain match replay with 1-5 stars (*, **, ...) [e.g. because it was a great victory, a defeat from which to learn or whatever the motivation may be]
* search for a certain player name in the matches list and set the first match with that player name to the top of the list
* use up/down buttons to display the next/previous match which has been fought against a certain foe
* get a view at all your decks with the buttons 'My Best SOLO Decks' and 'My Best Team Decks'

## IMPORTANT

***The tool does NO *cheating* at all!***

Of every new replay file that appears in the official folder it just creates an instant copy to a working folder.
The original file is **not** being touched in any other way!
The copied replay file is then being parsed for infomation about '*Master & Deck*', '*Win or Loss*' and '*Rank*'.
All the information provided by the tool could also be created by a player ***manually*** by using a **tally sheet** during a match or while watching the appropriate replay.

## Installation
The tool installation file ***MargaVBs Minion Masters Replays Manager Vx.xx.xx.exe*** provides an **installation wizard** which guides you through the installation process. Also provided with the installation is this **README.md** file which provides more information about installation and other aspects of the tool.

In order to install the tool follow the instructions of the **Installation Wizard**.
After installation the **main installation folder** (your name for the ***project-root/***) should contain the following files and folders:
```
project-root/ (whatever it was named during installation)
    ├── lib/
        ├── ...
    ├── resources/
        ├── Cards/
            ├── *.png
        ├── *.png
        ├── Gimmicks
    ├── Services/
        ├── ...
    ├── share/
        ├── ...
    ├── uninstall/
        ├── ...
    ├── Utils/
        ├── ...
    ├── Disclaimer.md
    ├── frozen_application_license.txt
    ├── MMReplayManager.exe
    ├── MMRMPatchNotes.md
    ├── python3.dll
    ├── python310.dll
    ├── Readme.md
    ├── Uninstal.exe
```

The Metadata that contain **all statistics** as well as the **work folders** and **autosave folders** can be found here:

```
C:\\Users\\[YOUR_USER_NAME]\\AppData\\LocalLow\\MinionMastersReplaysManager
    ├── MM_Replays_2_0
        ├── invalidReplays
        ├── Loosing
        ├── manageReplays
        ├── seasonBackups
        ├── tmp
        ├── Winning
    ├── DeckStorage_2_0.data
    ├── MetaData.data
    ├── OpponentStatistics.data
    ├── ReplayFileInfoNew.data
    ├── replayManager.log
    ├── StatisticReplays.data
```

There should also be a desktop icon **MM Replays Manager.ico** available on the desktop with which to start the tool.

## Requirements
* The **Minion Masters (BetaDwarf(C))** Game.
* A **monitor** with a ***resolution*** of at least **1920*1080**.

## Important Notes

**NOTE**: Display of rank is ***disabled*** for all match replays **before** *Minion Masters Version **2.6*** (parts of the replay file structure have changed in version **2.6**)

**NOTE**: The season end might **not** be detected properly!

**WARNING**: Deleted replays will be saved to a backup folder. If those files are being copied back to the original replay folder of **Minion Masters (BetaDwarf(C))** it may happen that they are **no longer compatible** with the **most recent version** of the game! This may produce ***issues/errors*** when trying to play them in the replay section of the game!

## Known bugs/issues:
A list has been added to the *patch notes*.

## Plans for the future
A list with ideas for the future has been added to the *patch notes*.

**Have fun! :)**

MargaVB
