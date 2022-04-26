# CyberSpy - Espía Cibernético
Hacking Tool Suite for Android in Termux **(No root)**
> This tool can only be executed in Termux.
## Preview in Termux
![CyberSpy](https://github.com/Darkmux/cyberspy/blob/main/images/CyberSpy.png)
## Requirements
* Updated Termux application.
* Android 7 or higher.
* Minimum 100MB of available storage.
## Download Termux F-Droid
> Note: It is not recommended to use the Termux application that is available in "Google Play Store" because the developers no longer maintain this app and therefore it is outdated.  Termux still receives updates on another platform called "F-Droid" so download the app with the following link:
[Termux F-Droid](https://f-droid.org/en/packages/com.termux)
## Installation in Termux
> Update Termux repositories.

```bash
yes|pkg update && pkg upgrade
```

> Grant storage permissions to Termux.

```bash
termux-setup-storage
```

> Install "git" version control software.

```bash
yes|pkg install git
```

> Clone github repository.

```bash
git clone https://github.com/Darkmux/cyberspy
```

> Access the cloned "cyberspy" folder.

```bash
cd cyberspy
```

> Grant execute permissions to all files with extension (.sh).

```bash
chmod 777 *.sh
```

> Run the installer.

```bash
bash cyberspy.sh
```
## New Commands Available
> The main command is `spy` which is used along with its arguments for it to work properly:
## Arguments Available
```bash
spy help
```
```bash
spy list <tools|banners>
```
```bash
spy update
```
```bash
spy uninstall
```
```bash
spy style <banner>
```
```bash
spy install <tool>
```
```bash
spy remove <tool>
```
## Social Media Links
* [Facebook](https://www.facebook.com/whitehacks00 "WHITE HACKS")
* [TikTok](https://tiktok.com/@whitehacks00 "WHITE HACKS")
* [Telegram](https://t.me/whitehacks00 "WHITE HACKS")
