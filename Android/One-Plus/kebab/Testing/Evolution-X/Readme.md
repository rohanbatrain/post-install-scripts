# Recovery
1. OrangeFox -> Best 

# Flashing evolutionx
1. adb sideload copy_partitions.zip
2. adb sideload evolutionx (Failed)
3. Normal adb sideload command wasn't working, so selected the zip and installed, then formatted Data partition
4. Rebooted 

# Magisk 
> Same as lineage, additional steps:

1. Hide magisk app - renamed to Rohan
2. enabled zygisk, added systemless hosts, enabled enforce deny list
3. reboot
4. Added Google play services, google play store to denylist, successfully passed [Safety-Net](https://github.com/RikkaW/YASNAC).


# Setup

> Creating 3 users

  1. Productivity ( Education, Finance, Obsidian, Business etc.)
  2. Entertainment ( Games, Socials etc.) 
  3. Harshdeep Singh ( Trusted Person Access ) 

> Restarting (Taking a backup in orangefox, and trying to change f2fs to ext4 using orangefox)

Why? I want symlinks on userspace, if i am right then i ccan get around the termux error of no permission while using ln -s.

Well it didn't work.


## Setting Productivity

> Apps 

1. Bitwarden
2. Aegis Authenticator
3. Obsidian
4. GPay
5. Tutanota
