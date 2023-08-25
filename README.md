# cross-platform-streaming

The following guide is very much the result of trial and error. It is not intended to be a definitive guide. It is a collection of notes to help you achieve a similar result to what I have achieved. Good luck!

The hardware I am using is as follows:
 - Mac Mini M1 2020
 -  Elgato Wave:3
 -  Standard PC speakers using the headphone jack of the Mac. They have a headphone out port also.

The software I am using is as follows:
 - MacOS Ventura 13.4 (22F66)
 - Google Chrome - for nostrnests.com
 - Safari - for YouTube Music
 - Android Studio - Giraffe | 2022.3.1 Patch 1 - https://developer.android.com/studio/
 - Android Virtual Device Manager
 - Loopback2 Version 2.2.13 from Rogue Amoeba - https://rogueamoeba.com/loopback/
 - BlackHole Virtual Audio Driver - https://github.com/ExistentialAudio/BlackHole

Step 1
 - Install BlackHole Audio Driver - this is essential as it allows you to pass outputs to your input channel.
 - Select the 2CH option
 - Sound settings will look like the following
<img width="471" alt="Screenshot 2023-08-25 at 18 10 33" src="https://github.com/8itcoinChris/cross-platform-streaming/assets/143212976/6e6aa32d-e594-4d33-8144-92dd51ab87c4">
<img width="473" alt="Screenshot 2023-08-25 at 18 10 44" src="https://github.com/8itcoinChris/cross-platform-streaming/assets/143212976/fffca6fa-075f-4cc4-bfd8-0db9061142e1">
 - In the Audio MIDI Setup, ensure the "Format" is set to 44,100hz
<img width="1020" alt="Screenshot 2023-08-25 at 18 11 23" src="https://github.com/8itcoinChris/cross-platform-streaming/assets/143212976/015e4fc6-8a76-4a2a-bfee-b529ad8d9681">
<img width="1013" alt="Screenshot 2023-08-25 at 18 11 36" src="https://github.com/8itcoinChris/cross-platform-streaming/assets/143212976/890b5d58-4933-424c-a384-3ed4fea6e91d">

Step 2
 - Install Android Studio
 - Create a virtual device
<img width="849" alt="Screenshot 2023-08-25 at 18 09 03" src="https://github.com/8itcoinChris/cross-platform-streaming/assets/143212976/eead9df5-1e0d-4a77-9619-143ea4f1e7a3">
 - Select a build that includes the Play Store. You will need this to download and install X
<img width="839" alt="Screenshot 2023-08-25 at 18 09 23" src="https://github.com/8itcoinChris/cross-platform-streaming/assets/143212976/a0b71482-5314-49d4-8fb8-534090e0efa4">
 - Launch your virtual device
 - Click the three dots on the right hand side of the emulator
 - Select the Microphone tab
 - Toggle on "Virtual microphone uses host audio input"
<img width="1040" alt="Screenshot 2023-08-25 at 18 09 54" src="https://github.com/8itcoinChris/cross-platform-streaming/assets/143212976/dfc48761-a4df-453d-b8c5-43fdaa837460">
 - Install X
 - Log in as normal

Step 3
 - Install Loopback
 - Close all other Mic software
 - This is how I have configured Loopback:
<img width="1134" alt="Screenshot 2023-08-25 at 18 05 45" src="https://github.com/8itcoinChris/cross-platform-streaming/assets/143212976/65bae1d4-94fe-466f-82c4-8c2cbcd49f4c">

Step 4
 - Open nostrnests.com on Google Chrome
 - Create a nest and ensure your Mic is not muted
 - Create a X Space, again ensuring your Mic is not muted
 - Use mute options on your external Mic instead of the streaming platform, otherwise you will stop each audience from being able to hear each other.

This is my typical screen layout
<img width="2559" alt="Screenshot 2023-08-25 at 18 08 03" src="https://github.com/8itcoinChris/cross-platform-streaming/assets/143212976/995ee42b-a3f6-4fa1-ac12-cf3b530f6630">

Important notes
 - I am performing a hard reboot before each streaming session
