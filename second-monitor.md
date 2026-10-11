# Second Monitor With Side Screen
My mac connect to android tablet became second monitor

### Tools Usage
Install sidescreen on mac and android
```
https://www.sidescreen.dev/
```

---


### On Your Mac
ADB Required: The Mac app needs adb to communicate with your Android device. If the app doesn't show "Running", install ADB first:

1. Install Homebrew

```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

2. Update your location homebrew *** Adjust YourMacUsername
```
echo >> /Users/YourMacUsername/.zprofile
echo 'eval "$(/opt/homebrew/bin/brew shellenv zsh)"' >> /Users/YourMacUsername/.zprofile
eval "$(/opt/homebrew/bin/brew shellenv zsh)"
```

3. Install ADB
```
brew install --cask android-platform-tools
```

4. Download SideScreen-0.11.3-mac-universal.dmg
```
https://github.com/tranvuongquocdat/SideScreen/releases/tag/0.11.3
```

---

### On Your Android
ADB Required: The Mac app needs adb to communicate with your Android device. If the app doesn't show "Running", install ADB first: