# mac-setup

Hexalellogram's macOS Setup Scripts

## Download and Run:
Paste this into the macOS Terminal:

`curl -LOk https://github.com/hexalellogram/mac-setup/archive/master.zip && unzip -a master.zip && rm master.zip && cd mac-setup-master && chmod +x ProgramInstall.sh && ./ProgramInstall.sh`

## Prerequisites
- [Xcode.app or Xcode-beta.app](https://developer.apple.com/download/) installed

## Binaries Installed via Homebrew
- `mas`
- `wget`
- `tree`
- `m-cli`
- `archey`
- `hub`
- `trash`
- `thefuck`
- `dos2unix`
- `boxes`

## GUI Applications Installed

### Core/Essentials
- [1Password Beta](https://1password.com)
- [Steam](http://store.steampowered.com/about/)
- [Karabiner Elements](https://github.com/tekezo/Karabiner-Elements)
- [Google Chrome](https://www.google.com/chrome/browser/desktop/index.html)
- [Insync](https://www.insynchq.com)
- [BetterTouchTool](https://www.boastr.net) ([Custom Settings](https://github.com/hexalellogram/mac-setup/wiki/BTT-Shortcuts) automatically imported)
- [Carbon Copy Cloner](https://bombich.com)
- [Spotify](http://spotify.com)
- [Microsoft Office](https://www.office.com)
- [VMware Fusion](https://www.vmware.com/products/fusion.html)
- [YakYak](https://github.com/yakyak/yakyak)

### Menubar Apps
- [Dropbox](https://www.dropbox.com/?landing=dbv2)
- [Google Backup and Sync](https://drive.google.com) 
- [OneDrive Standalone](https://support.office.com/en-us/article/New-OneDrive-sync-client-release-notes-845dcf18-f921-435e-bf28-4e24b95e5fc0) (See the "separate download" link under the Downloads header)
- [NordVPN](https://nordvpn.com)
- [Semulov](https://github.com/kainjow/Semulov)
- [Spotify Notifications](https://spotify-notifications.citruspi.io)
- [MenuMeters (Yujitach Port)](https://member.ipmu.jp/yuji.tachikawa/MenuMetersElCapitan/)
- [Brightness Menulet](https://github.com/superduper/BrightnessMenulet)
- [RescueTime](https://www.rescuetime.com)
- [Itsycal](https://www.mowglii.com/itsycal/)
- [WhatPulse](https://whatpulse.org/)
- [Synergy](http://symless.com/)
- [Bartender](https://www.macbartender.com/)

### [Objective-See](https://objective-see.com/) Security Apps
- [BlockBlock](https://objective-see.com/products/blockblock.html)
- [OverSight](https://objective-see.com/products/oversight.html)
- [RansomWhere](https://objective-see.com/products/ransomwhere.html)
- [What's Your Sign?](https://objective-see.com/products/whatsyoursign.html)

### Code/Computer Science Apps
- [GitKraken](https://www.gitkraken.com)
- [Java JDK](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)
- [Java 6](https://support.apple.com/kb/DL1572) (Temporary fix for IntelliJ IDEA menu bar on High Sierra)
- [IntelliJ IDEA](https://www.jetbrains.com/idea/)
- [Eclipse Java IDE](http://www.eclipse.org)
- [Visual Studio Code](https://code.visualstudio.com)
- [PowerShell](https://github.com/PowerShell/PowerShell)

### Other Apps/Utilities
- [Adobe Acrobat Reader](https://get.adobe.com/reader/)
- [Android File Transfer](https://www.android.com/filetransfer/?linkid=14270770)
- [AppCleaner](http://freemacsoft.net/appcleaner/)
- [The Unarchiver](https://theunarchiver.com)
- [Keka](http://www.kekaosx.com/en/)
- [Tuxera NTFS](http://www.tuxera.com/products/tuxera-ntfs-for-mac/)
- [FUSE for macOS](https://osxfuse.github.io)
- [Android Platform Tools](https://developer.android.com/studio/releases/platform-tools.html) (`adb`, `fastboot`, etc.)
- [Transmission](https://transmissionbt.com)
- [MakeMKV](https://www.makemkv.com)
- [Handbrake](https://handbrake.fr)
- [MetaZ](https://griff.github.io/metaz/)
- [Silverlight](https://www.microsoft.com/silverlight/)
- [NGROK](https://ngrok.com)
- [Firefox](https://www.mozilla.org/en-US/firefox/?utm_medium=referral&utm_source=firefox-com)
- [Zoom.us](https://www.zoom.us/)
- [IINA](https://lhc70000.github.io/iina/)
- [Opera](https://www.opera.com/computer)

### Finder Quick Look Generators
- [BetterZipQL](https://macitbetter.com/BetterZip-Quick-Look-Generator/)
- [QLColorCode](https://github.com/n8gray/QLColorCode)
- [QLMarkdown](https://github.com/toland/qlmarkdown/)
- [QLStephen](https://github.com/whomwah/qlstephen)

### Mac App Store Apps
- [Amphetamine](https://itunes.apple.com/us/app/amphetamine/id937984704?mt=12)
- [Pages](https://www.apple.com/pages/)
- [Keynote](https://www.apple.com/keynote/)
- [Numbers](https://www.apple.com/numbers/)
- [iMovie](https://www.apple.com/imovie/)


### Steam Games
- [Team Fortress 2](http://www.teamfortress.com)
- [Kerbal Space Program](https://kerbalspaceprogram.com/en/)
- [Planetary Annihliation](http://www.uberent.com/pa-classic/)
- [Civilization V + DLC](http://www.civilization5.com)
- [Rocket League](https://www.rocketleague.com)

### Programs That Must Be Installed Manually
- [Winclone](https://twocanoes.com/products/mac/winclone/)

## Other Stuff Configured
- [Touch ID PAM Module](https://github.com/hamzasood/pam_touchid)
- macOS System Settings ([Read echo statements here for details](https://github.com/hexalellogram/mac-setup/blob/master/SystemSettings.sh))
- Create folder `~/Temp`
- San Francisco [Pro Display](https://developer.apple.com/fonts/), [Pro Text](https://developer.apple.com/fonts/), and [Mono](https://simonfredsted.com/1438) Fonts Installed
- Terminal configured to my custom settings (see [Pro Modified.terminal](https://github.com/hexalellogram/mac-setup/blob/master/ProModified.terminal))
- Startup applications configured as per my preferences
- `git pullall` - see file `git-pullall`

## Other Stuff You Might Need to Know
- [Code of Conduct](https://github.com/hexalellogram/mac-setup/blob/master/CODE_OF_CONDUCT.md)
- This project is licensed under the [MIT License](https://github.com/hexalellogram/mac-setup/blob/master/LICENSE)

