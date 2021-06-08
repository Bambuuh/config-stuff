# config-stuff

## icanhazshortcut
android shake: ANDROID_HOME=$HOME/Library/Android/sdk && $ANDROID_HOME/platform-tools/adb shell input keyevent KEYCODE_MENU
android reload: ANDROID_HOME=$HOME/Library/Android/sdk && $ANDROID_HOME/platform-tools/adb shell input keyevent KEYCODE_MENU && $ANDROID_HOME/platform-tools/adb shell input keyevent ENTER && $ANDROID_HOME/platform-tools/adb shell input keyevent ENTER

## oh my zsh
vim mode: set -o vi
