# Useful Android phone modifications through the command line 

## Removing unwanted apps
Sometimes phones come with useless apps that don't have the option to remove them from the phone itself. Luckily,there is a very easy way of doing it from a computer. I removed all the google bloatware from my phone. Goodbye youtube music, youtube, google assistant, pixel tips and other apps that I have never touched since I got this phone.

The command for removing an app is `adb shell pm uninstall -k --user 0 (path.to.the.app)`. For example, if we want to remove Youtube Music from my Pixel 8a, the command would be `adb shell pm uninstall -k --user 0 com.google.android.apps.youtube.music`. The paths to popular apps are available online or through the file explorer. AND do not remove important apps obviously.

