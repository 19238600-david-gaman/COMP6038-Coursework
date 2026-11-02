# Live Caption Headset (COMP6038)

A Meta Quest 3 app that listens to speech and shows live English captions over the passthrough view. Everything runs on the headset itself, with no server and no internet needed. It starts with Spanish to English, and Mandarin to English will be added after if the initial testing is successful.

## How it works
1. The headset mic picks up speech.
2. Whisper (via [whisper.unity](https://github.com/Macoron/whisper.unity)) translates it to English on the device.
3. Captions appear in a panel in passthrough.

## Built with
- Unity, with Android build support
- Meta XR SDK
- whisper.unity, using the Whisper Tiny multilingual model

## Getting started
1. Clone the repo and open it in Unity.
2. Download `ggml-tiny.bin` into `Assets/StreamingAssets/Whisper/`. It isn't committed because it's too big.
3. Test in the editor with your laptop mic, then build to the Quest over USB.

## Team
Santiago Suarez Barajas, Robert Noble, Maxwell Emmanuel, Ugur Yildiz, David Gaman.

## Contributing
Work on a branch and open a pull request. Nothing goes straight to `main`.
