# adb-newbie
ADB command document.

## Commands
- Make a phone call
  - `am start -a android.intent.action.CALL -d tel:"Telephone Number"`
- Close an app
  - `am kill com.your.package`
- Back to homescreen
  - `input keyevent KEYCODE_HOME`
