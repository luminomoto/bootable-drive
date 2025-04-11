# How to Make Bootable Storage for OS Installation with Bypass Feature

*before we start make sure you have stable internet connection*

Requirements:
1. Flash Drive (8GB Recommended, bawal ung fake na nabibili na tig 300 sa shopee neh sasabog yan.) <br><br>
2. ISO File (the OS copy.)
<br><br>
**Step 1:** Click the link <a href="https://github.com/pbatard/rufus/releases/download/v4.7/rufus-4.7.exe">here</a> to download the file. <br><br>
**Step 2:** Insert the flash drive to your PC/Laptop <br><br>
**Step 3:** Open rufus.exe <br><br>
**Step 4:** Click "SELECT" and Load the ISO File. <br><br>

**Partition scheme & Target System:**<br>
**MBR** for legacy BIOS <br>
**GPT** for UEFI systems <br>
**Target system** will auto-adjust, but you can change it based on your system.<br><br>
**File System & Cluster Size:**<br>
Usually **FAT32** or **NTFS** is fine (Rufus sets it automatically).<br>
Leave cluster size to default. <br><br>

<b>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Step 5:</b> Start the Process. <br><br>

*optional: you can select what you want to bypass.* <br><br>

After the Process Completed, Eject your Flash Drive.
