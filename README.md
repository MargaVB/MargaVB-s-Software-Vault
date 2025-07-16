# MargaVB's Minion Masters Replays Manager

This is a **tool** for the game '**Minion Masters**' ( (C) ***BetaDwarf*** ).

## Every new version of the tool will be available via one of the following links:

**Version 1.4.4:** [Direct Download Here](https://drive.google.com/uc?export=download&id=17u5ob5WztAoUgLlxZh48IEBCs8ovDRRM)

or click on:

1. [MargaVB's Discord](https://discord.gg/wTJzRUBMAD)
1. [Github repository](https://github.com/MargaVB/MargaVB-s-Software-Vault)

#### **NOTE**: The download from Google Drive may not be able to finish a virus scan properly. It only scans Documents, PDFs, and images, **not** '***.exe files***'. Here are the results from VirusTotal as an alternative:

---

![MMReplayManager.exe](https://github.com/MargaVB/MargaVB-s-Software-Vault/blob/main/VirusTotal_MMRM.png)

![MargaVB's Minion Masters Replays Manager V1.4.4.exe](https://github.com/MargaVB/MargaVB-s-Software-Vault/blob/main/VirusTotal_MMRM_Wizard.png)

---

As you can see the ***'MargaVB's Minion Masters Replays Manager'*** **exe file** is **not flagged at all** by any of the maleware detections. The ***Install Wizards File*** is being flagged by only two malware detectors out of them all. Both are known for **flagging everything** that has not been uploaded to their whitelisting database. Maybe they would like to charge developers for adding their software to the whitelist.

## Purpose Of The Tool

* get overall statistics for all matches since first start of this tool (all time wins/losses, all time winratio)
* get statistics for a certain 'Master & Deck' combination of yours (wins/losses and win ratio)
* get info about all replays: own/opponent's master, deck and rank at that time, all wins/losses and win ratio with that deck
* get info about the ELO values of players that took partition in a certain match (uses the website supported by Minion Masters)
* get a view at all your decks with the buttons [*My Best SOLO Decks*] and [*My Best TEAM Decks*]
* mark a certain match replay with 1-5 stars (*, **, ...) [e.g. because it was a great victory, a defeat from which to learn or whatever the motivation may be]
* delete matches (the most recent one, the ones marked by star(s), or delete all). All replays are moved to a backup folder, you can restore them
* search for a certain player name in the matches list and scroll to the first entry with a match against that player
* use up/down buttons to display the next/previous match which has been fought against the same opponent

## IMPORTANT

***This tool does NOT involve any form of cheating!***

Whenever a new replay file appears in the official folder, the tool instantly creates a copy in a working folder. The original file remains untouched! Only the copied version is parsed for relevant information. All the data provided by the tool could just as well be recorded ***manually*** by a player using a **tally sheet** during a match or while reviewing a replay.

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
            ├── *.png
        ├── RankIcons
            ├── *.png
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
    ├── MetaData.data
    ├── replayManager.log
    ├── MM_Replays_2_0
        ├── invalidReplays
        ├── Loosing
        ├── manageReplays
        ├── seasonBackups
        ├── tmp
        ├── Winning
C:\\Users\\[YOUR_USER_NAME]\\AppData\\LocalLow\\MinionMastersReplaysManager_[YOUR_USER_ID]
    ├── MM_Replays_2_0
        ├── invalidReplays
        ├── Loosing
        ├── manageReplays
        ├── seasonBackups
        ├── tmp
        ├── Winning
    ├── DeckStorage_2_0.data
    ├── OpponentStatistics.data
    ├── ReplayFileInfoNew.data
    ├── StatisticReplays.data
C:\\Users\\[YOUR_USER_NAME]\\AppData\\LocalLow\\MinionMastersReplaysManager_[YOUR_USER_ID]_1
    ├── MM_Replays_2_0
        ├── invalidReplays
        ├── Loosing
        ├── manageReplays
        ├── seasonBackups
        ├── tmp
        ├── Winning
    ├── DeckStorage_2_0.data
    ├── OpponentStatistics.data
    ├── ReplayFileInfoNew.data
    ├── StatisticReplays.data
C:\\Users\\[YOUR_USER_NAME]\\AppData\\LocalLow\\MinionMastersReplaysManager_[YOUR_USER_ID]_2
    ├── MM_Replays_2_0
        ├── invalidReplays
        ├── Loosing
        ├── manageReplays
        ├── seasonBackups
        ├── tmp
        ├── Winning
    ├── DeckStorage_2_0.data
    ├── OpponentStatistics.data
    ├── ReplayFileInfoNew.data
    ├── StatisticReplays.data
C:\\Users\\[YOUR_USER_NAME]\\AppData\\LocalLow\\MinionMastersReplaysManager_[YOUR_USER_ID]_3
    ├── MM_Replays_2_0
        ├── invalidReplays
        ├── Loosing
        ├── manageReplays
        ├── seasonBackups
        ├── tmp
        ├── Winning
    ├── DeckStorage_2_0.data
    ├── OpponentStatistics.data
    ├── ReplayFileInfoNew.data
    ├── StatisticReplays.data
```

There should also be a desktop icon **MM Replays Manager.ico** available on the desktop with which to start the tool.

## Requirements
1. The **Minion Masters (BetaDwarf(C))** Game.
1. A Windows OS (**Win7**, **Win10** or **Win11** recommended, **Linux** might be supported in a later version)
1. A **monitor** with a ***resolution*** of at least **1920*1080**.

## Important Notes

### Uninstallation

The tool can be ***uninstalled*** via the **windows app settings**. The ***work folders***, ***statistics*** and ***meta data*** files are located in

```
C:\\Users\\[YOUR_USER_NAME]\\AppData\\LocalLow\\
```

organized in **subfolders** being described in the section **above** (*Installation*). These folders are **not** uninstalled automatically by the *uninstaller* and therefore have to be removed **manually**!

### Rank display

Display of rank is ***disabled*** for all match replays **before** *Minion Masters Version **2.6*** (parts of the replay file structure have changed in version **2.6**)

### Season End

The season end might **not** be detected properly! *The Minion Masters game app* keeps **500 replays** on a *season switch* and **removes all exceeding replays** as soon as the *replay section* has been activated ingame.

**WARNING**: Deleted replays will be saved to a backup folder. If those files are being copied back to the original replay folder of **Minion Masters (BetaDwarf(C))** it may happen that they are **no longer compatible** with the **most recent version** of the game! This may produce ***issues/errors*** when trying to play them in the replay section of the game! This should not be a problem though for replays which were created **after** the development on *Minion Masters* had been stopped.

## Known bugs/issues:
A list has been added to the *patch notes*.

## Plans for the future
A list with ideas for the future has been added to the *patch notes*.

**Have fun! :)**

MargaVB
