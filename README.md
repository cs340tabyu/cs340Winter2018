# cs340Winter2018

How to install the APK on your emulator:
 1. Navigate to the platform-tools directory in your Android folder. Found on my machine at `cd ~/Library/Android/sdk/platform-tools/`
 2. Copy the ticketToRide.apk to this directory.
 3. Open your emulator via Android Studio (Pixel C APK 26 Landscape).
 4. Run this command to install APK to the emulator `./adb install ticketToRide.apk`
 5. Go to the device, look for app called TicketToRide, click to launch.
