# ScreenShotVRC
ScreenShot with Steam

# Installation
## Out Line

- Install VaNiiMenu
- Install RecordVRCWithGeForceExperience
- Setup the VaNiiMenu

## Install VaNiiMenu
Download VaNiiMenu: refer to https://sabowl.sakura.ne.jp/gpsnmeajp/unity/vaniimenu/
Please extract to any directory: I recommend to put on `C:\VaNiiMenu`

## Install ScreenShotVRC
Download ScreenShotVRC by https://github.com/forno/ScreenShotVRC/releases
Please extract to any directory: I recommend to put on `C:\ScreenShotVRC`

## Setup The VaNiiMenu
Please fix `/path/to/VaNiiMenu/config/Launcher.json` with

```json
"App1": {
	"ApplicationName": "ScreenShot VRC",
	"FilePath": "screenShotVRC.bat",
	"WorkingDirectory": "C:\\screenShotVRC",
	"Arguments": "",
	"StartupDialogMainText": "Take screen shot?",
	"StartupDialogSubText": "stream cameraでのスクショ"
},
```

Note: You should fix WorkingDirectory path to your install directory. (if you follow my recommendations, you just do nothing)

Here are my settings. You just replace values for any "Appx".

## Finish
You just see `ScreenShot VRC` in the Lunch menu on VaNiiMenu.

# Usage
## RecordVRC
You pick up the stream camera then launch the `ScreenShot VRC`.
You get ScreenShot by steam screenshot.
