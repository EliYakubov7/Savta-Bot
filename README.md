# SavtaBot

Created for the elderly who sometimes suffers from a lack of communication with the environment.

SavtaBot is an Android app, impleminting Google's DialogFlow and TTS services.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

What things you need to install the software and how to install them

Install [Android Studio](https://developer.android.com/studio) on your PC.


### Installing

Clone this repository and import into **Android Studio**.
```bash
https://github.com/EliYakubov7/SavtaBot.git
```
Go to **File -> New -> Project from Version Control -> Git**

## Run on Android

-	`APK` - Using Android Studio. Build -> Build Bundle(s) / APK(s) -> Build APK(s)
-	`Run directly` -  Connect Android device or use AVD. Run -> Run 

### Your own SavtaBot

- Create a new project in [DialogFlow](https://dialogflow.cloud.google.com).
- Go to your Agent settings and copy your unique *Client access token*.
- In MainActivity.java <line 81> past your access token.
- Run application.

## Screenshots

<img src="https://github.com/EliYakubov7/SavtaBot/blob/master/screenshots/splash_screen.png" width="250"> <img src="https://github.com/EliYakubov7/SavtaBot/blob/master/screenshots/chat_box.png" width="250">  
<img src="https://github.com/EliYakubov7/SavtaBot/blob/master/screenshots/settings.png" width="250">  <img src="https://github.com/EliYakubov7/SavtaBot/blob/master/screenshots/microphone.png" width="250">  

## Authors

* **Eliyahu Yakubov** - *Initial work* - [Eliyahu Github](https://github.com/EliYakubov7), [Linkedin](https://www.linkedin.com/in/eli-yakubov-961908173)
* **Gal Reshef S** - *Initial work* - [Gal Github](https://github.com/galsreshef)
