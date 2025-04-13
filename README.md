## Wear Companion
![Static Badge](https://img.shields.io/badge/Wear%20OS%20Test%20App-Kotlin)

This is a Kotlin Wear OS app made to check the connection capabilities of Data Layer API for setting up a bidirectional communication.

I know the UI looks like trash, but this is made just to make sure that the communication will not be an issue.

[Demo Video](https://www.youtube.com/watch?v=i7tVZb8hycA)


## Features
- Establishes a connection with a paired phone.
- Sends custom messages from watch to phone.
- Receives and displays messages from the phone.


## Technologies Used
- Kotlin – Native language.
- Jetpack Compose – This is for UI. 
- Wearable Data Layer API – Used to communicate with devices.
  - MessageClient – For sending/receiving point-to-point messages.


## Permissions Used
The app uses the following permissions:

```
<uses-permission android:name="android.permission.WAKE_LOCK" />
```
Ensures the watch stays awake while sending/receiving messages.


## Local Setup
You will be needing two repos in total in order to test this app as this is the WearOS companion, and then there is [Mobile Companion](https://github.com/Abhishek14104/mobile_companion) app for this as well.

1. Clone the Repository
   ```bash
   git clone https://github.com/Abhishek14104/wear_companion.git
   ```

2. Open in Android Studio

3. Run on any Wear OS device or emulator


**Before testing make sure that your Android Device is connected to the WearOS Watch properly.**
