# WhisperVoiceInput

## Status of the project

Voice Input is currently being developed as a [https://futo.org](FUTO) project and will launch soon. It will come with a polished UI, the option to switch models, multilingual support, and various improvements.

This repository contains an old version of the code that served as the initial proof-of-concept.

## Info about this repo

Android app to perform voice input using tflite Whisper model locally.

Some usage notes:
* Android apps have several methods of performing voice input, this app currently implements only the intent method (`android.speech.action.RECOGNIZE_SPEECH`)
* The intent method isn't supported by AOSP keyboard or OpenBoard, so you need to use AnySoftKeyboard for keyboard integration
* Some apps like Firefox, Chrome, Organic Maps will also gain a voice input button after the app is installed, allowing you to do voice input that way
* The APK size is currently huge and not optimized
* Interaction with other installed voice input providers has not been tested