# GoAwayAssistant

[Per Google:](https://support.google.com/gemini/answer/14579026)
"Android Go doesn't support the Gemini mobile app."
Well, now it does ;)

## What does this actually do?

This module systemlessly removes the Android Go Google Assistant app (AKA com.google.android.apps.assistant) so the regular Google app can be installed. This can be installed alongside the Google Go app, but this is not required.

## What does this allow?

This allows the usage of the many features inside the Google app. These include Gemini, Lens, and more. 2GB of RAM is not needed with this process, so you may continue even if you have a device with less.

## What do I need?

* A device with Magisk v29+ or similar (support for REMOVE is needed).
* APK files for the Google app. These can be obtained either through APKMirror, or Aurora Store spoofed as the Samsung Galaxy A13 5G (use J5 Prime for devices with Android 11 or lower).
* Android 9 or higher (Google app limitation).
* An affected device.

## How do I install the module?

This is a fairly simple module. Simply install it as normal, reboot, and you will find that the Assistant Go app is now missing. If you want extra verification, try using ``cmd package install-existing com.google.android.apps.assistant`` in an adb or local shell. If this command fails, the module worked. 

Once you have done this. Install the Google app using your preferred method. If you are using the Aurora Store method, and the aforementioned spoofs are not available, please try the latest nightly build.

## Can I set Gemini as my assistant?

Yes. Simply switch your default "Assist" or "Assistant" app in Settings to Google. When you hold down the home button, Gemini should appear and work as normal.

## Questions?

Feel free to make a GitHub issue. I will read and respond in due time.
