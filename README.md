# ProjectMod04.
How to boot usb

Download and Install Rufus:

Visit the Rufus website and download the latest version of Rufus (it's portable, so no installation is necessary).
Insert Your USB Drive:

Plug your USB drive into the computer.
Launch Rufus:

Open the Rufus application. It should automatically detect your USB drive.
Select the Bootable ISO File:

Click on Select under the "Boot selection" section.
Choose the ISO file of the operating system or utility you want to put on the USB drive (e.g., a Linux distro or Windows ISO).
Configure Partition Scheme:

For most modern systems, set Partition Scheme to GPT (for UEFI systems) or MBR (for BIOS systems).
For File System, choose FAT32 if the file size is under 4GB, or NTFS for larger files.
Start the Process:

Click on Start. You may be prompted to select Write in ISO Image mode (recommended).
Warning: This will erase all data on the USB drive, so make sure you've backed up anything important.
Wait for Completion:

Rufus will format the USB and copy the ISO contents to make it bootable. This process can take several minutes.
Boot from USB:

Once done, safely eject the USB drive. To boot from it, restart your computer and enter the BIOS or boot menu (usually by pressing a key like F12, ESC, or DEL during startup).
Select the USB drive from the boot menu to boot from the USB.

# https://www.wikihow.com/Make-a-USB-Bootable
