# WhisperVoiceInput

## Status of the project

Voice Input is being developed as a [FUTO](https://futo.org/) project. [Click here to visit the FUTO Voice Input website.](https://voiceinput.futo.org/) More links:
* [FUTO Voice Input source code](https://gitlab.futo.org/alex/voiceinput)
* [Issue tracker for FUTO Voice Input](https://github.com/futo-org/voice-input/issues)

This repository contains an old version of the code that served as an initial proof-of-concept. Please look above for the full application.

## Info about this repo

Android app to perform voice input using tflite Whisper model locally.

Some usage notes:
* Android apps have several methods of performing voice input, this app currently implements only the intent method (`android.speech.action.RECOGNIZE_SPEECH`)
* The intent method isn't supported by AOSP keyboard or OpenBoard, so you need to use AnySoftKeyboard for keyboard integration
* Some apps like Firefox, Chrome, Organic Maps will also gain a voice input button after the app is installed, allowing you to do voice input that way
* The APK size is currently huge and not optimized
* Interaction with other installed voice input providers has not been tested