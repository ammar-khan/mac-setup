### First Time MacOS Setup
---
#### System Update
The first thing you should do is update your system. 
```
Apple menu > About This Mac > Software Update.
```
#### Users & Groups
- Personalise Login Options

#### Trackpad
- Personalise Point & Click
- Personalise Scroll & Zoom

#### Dock
- Personalise Visual Settings

#### Finder
- Personalise General Settings
- Personalise Sidebar

#### Menubar
- Personalise Menubar

#### Spotlight
- Personalise with https://www.alfredapp.com/

#### Accounts
- Add an iCloud account and sync Calendar, Find my Mac, Contacts...

#### Defaults
Enable repeating keys by pressing and holding down keys.
Run the following command in terminal
```
defaults write NSGlobalDomain ApplePressAndHoldEnabled -bool false
```
Change the default folder for screenshots.

Open the terminal and create the folder where you would like to store your screenshots
```
mkdir -p /path/to/screenshots/
```
Run the following command in terminal
```
defaults write com.apple.screencapture location /path/to/screenshots/ && killall SystemUIServer
```