# Turn Your Old PSP-2000/3000 into a Nightstand Clock/Calendar

![thumbnail](https://github.com/itskme/PSP-Clock-AiO/assets/160423464/023c9488-768e-46bd-a11d-ebd835749304)

---

The PSP is still a great console despite having been released almost two decades ago. So, when you're not using it, why should it be collecting dust?

Introduce the PSP Clock. Originally an exclusive feature to the PSP GO, some crafty hackers ported the feature to the ordinary PSP about a decade ago. Combined with a custom 3D-Printed stand, it is the perfect way to keep the PSP alive and well. 

---

# Steps to Install PSP Clock Software

THE FOLLOWING INSTRUCTIONS APPLY TO ARK-4 CFW, USE OTHER CFW AT YOUR OWN RISK. **THIS WILL *NOT* WORK ON PSP-1000!**

### 1. Ensure you are running the latest version of the ARK-4 CFW on software version 6.61.

If you on an older version of PSP firmware (6.60 or older), this guide may not work. For steps on upgrading your CFW to ARK-4 if you already on v6.61, please read this [excellent tutorial by pspunk](https://www.pspunk.com/chronoswitch/) which covers the process in-depth. If you want to upgrade the base firmware (ex: 6.60  -> 6.61) please read [this.](https://www.pspunk.com/psp-update/)

## 2. Download ZeroVSH Patcher [here](https://github.com/NightStar3/zerovsh-patcher/releases/download/0.4/ZeroVSH_Patcher_v0.4.BIN.zip)

## 3. Download ZeroVSH [here](https://www.mediafire.com/file/e44tzj1s2s92fqd/Installing_ZeroVSH_v0.2.rar/file)

## 4. Plug the PSP into a PC

Plug your PSP-2000 or PSP-3000 into your computer with a data-capable USB cable.  **Make sure the storage size that appears on the PC is the same as your MemoryStick.**

## 5. Copy ZeroVSH Patcher to PSP

To do this, copy **zerovsh.ini** and **zerovsh_patcher.prx** to Removable Disk:\SEPLUGINS\

## 6. Edit zerovsh.ini

In the same folder, open zerovsh.ini by double clicking it. Then, under the SlidePlugin section, change **ClockAndCalendar** from **Disabled** to **Enabled.** then save and close the file.

## 7. Edit PLUGINS.txt

    a.)    Open your SEPLUGINS folder on the PSP. Then, open **PLUGINS.txt.** If the file             does not exist, create it. 

    b.)    Add this line to the file: **vsh, ms0:/seplugins/zerovsh_patcher.prx, on**

    c.)    Save and close the file.

## 8. Create VSH Folder on PSP

Go to **Removable Disk:/PSP/VSH**. If this VSH folder does not exist, make it. 

Then, copy the contents of **ZeroVSH PATCHER/bin/slide** to **Removable Disk:/PSP/VSH**. 

There should now be three files in **Removable Disk:/PSP/VSH**. 

## 9. Copy more files to the PSP

Go to **Removable Disk:/PSP/VSH**. 

Then, copy the contents of **Installing ZeroVSH/main/VSH** to **Removable Disk:/PSP/VSH**.

There should now be 30 files in **Removable Disk:/PSP/VSH**.

## 10. Finalize on the PSP

Eject the PSP from your computer and press the SELECT button. 

Use the d-pad and X button to select and press **RESET VSH**. 

## 11. Enjoy!

Once everything is done, press the HOME button on the PSP to toggle the clock interface.

From there, press both shoulder buttons at once to toggle the calendar. 

---

# 3D printable stand

I designed this stand to hold the PSP while in clock mode. Feel free to edit the .IPT file to make changes of your own, or just print the .STL.
