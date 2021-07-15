# config-stuff

## icanhazshortcut
https://github.com/deseven/iCanHazShortcut


android shake: `ANDROID_HOME=$HOME/Library/Android/sdk && $ANDROID_HOME/platform-tools/adb shell input keyevent KEYCODE_MENU`


android reload: `ANDROID_HOME=$HOME/Library/Android/sdk && $ANDROID_HOME/platform-tools/adb shell input keyevent KEYCODE_MENU && $ANDROID_HOME/platform-tools/adb shell input keyevent ENTER && $ANDROID_HOME/platform-tools/adb shell input keyevent ENTER`

## oh my zsh
`brew install zsh`

vim mode: `set -o vi`

## Key repeat
`defaults write NSGlobalDomain KeyRepeat -int 1`

`defaults write NSGlobalDomain InitialKeyRepeat -int 10`

`defaults write NSGlobalDomain ApplePressAndHoldEnabled -bool false`

maybe

`defaults write com.apple.Accessibility KeyRepeatEnabled -bool 0`

## OSX
divvy

alfred

vimac
https://vimacapp.com/

alfred
https://www.alfredapp.com/

f.lux
https://justgetflux.com/

karabiner-elements
https://karabiner-elements.pqrs.org/

  - Simple - caps lock -> escape
  -  Comples - Change Control + h/j/k/l to Arrows
