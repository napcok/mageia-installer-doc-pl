# Odinstalowywanie Magei


If Mageia didn't convince you or you can't install it correctly, in short you want get rid of it. That is your right and Mageia also gives you the possibility to uninstall. This is not true for every operating system.

After your data backup, reboot your installation Mageia DVD and select Rescue system, then, Restore Windows boot loader. At the next boot, you will only have Windows with no option to choose your operating system.

To recover the space used by Mageia partitions on Windows, click on Start -> Control Panel -> Administrative Tools -> Computer Management -> Storage -> Disk Management to access to the partition management. You will recognize the Mageia partition because they are labeled Unknown, and also by their size and place in the disk. Right click on each of these partitions and select Delete. The space will be freed.

If you are using Windows XP, you can create a new partition and format it (FAT32 or NTFS). It will get a partition letter.

If you have Vista or 7, you have one more possibility, you can extend the existing partition that is at the left of the freed space. There are other partitioning tools that can be used, such as gparted, available for both windows and linux. As always, when changing partitions, be very careful, and make sure all important things have been backed up.
