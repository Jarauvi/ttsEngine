<div align="center">
  <img src="https://github.com/Jarauvi/organicmaps/blob/master/savonian_coa.png" height="100"/>
</div>
<h1 align="center"">SherpaTTS - Savonian edition</h1>

This is a fork of awesome [SherpaTTS](https://github.com/woheller69/ttsEngine) by woheller69!

I wanted to allow the use of this specific custom [Esa Pakarinen](https://en.wikipedia.org/wiki/Esa_Pakarinen) piper model as a navigator voice more easily than sending it to the phone using ADB, so I decided to create small startup script that copies the custom model in-place to modelDir when app is started at the first time.

Model cannot be changed to another or it is lost and reinstall is needed.

Model is used to convert the Finnish voice instructions of [Organic Maps](https://github.com/organicmaps/organicmaps) to god tier [Savonian](https://en.wikipedia.org/wiki/Savonian_people) accent! Check out [that repository](https://github.com/Jarauvi/organicmaps)

Demonstration video:

[![Watch the video](https://img.youtube.com/vi/nTjUuRwqrVk/0.jpg)](https://www.youtube.com/watch?v=nTjUuRwqrVk)

## Installation
- Download apk from [Releases](https://github.com/Jarauvi/ttsEngine/releases) page
- Allow phone to install apps from unknown sources
- Install the apk
- Start SherpaTTS for the first time - do not change the model! You can test output if you want
- Make SherpaTTS default TTS engine in Android preferences: System -> Languages -> Text-to-speech output -> Preferred engine

## Notes
I encountered a bug (?) where TTS language selection dropdown is flooded with 'Finnish' after setting up SherpaTTS. After reinstall, everything worked as expected.
