# MNB Recorder (Android)

Three tools in one app (Android 10+):
1. Screen recording: HD 720p/1080p, microphone + internal audio mixed. Saved to Movies/MNB Recorder.
2. Black screen camera: records camera video with sound, keeps going with the screen black or the phone locked. Saved to Movies/MNB Recorder.
3. Auto call recording: records every call (microphone; use SPEAKER). Saved to Recordings/MNB Call Recorder (Android 12+) or Music/MNB Call Recorder (Android 10-11).

## Build the APK online (no PC software needed)
1. Create a free account at github.com and make a new repository.
2. Upload ALL files of this folder (including the hidden .github folder).
3. Open the Actions tab, wait for "Build MNB Recorder APK" to finish (about 5 minutes).
4. Open the finished run, download the "MNB-Recorder-APK" artifact, unzip it, and install app-debug.apk.

## Build with Android Studio
Open this folder, wait for Gradle sync, then Build > Build APK(s).
APK path: app/build/outputs/apk/debug/app-debug.apk

## Tips for locked-screen recording
Settings > Apps > MNB Recorder > Battery > set to Unrestricted, so the phone does not stop the app.

## Limits
- Android blocks normal apps from recording the call stream. Call recording uses the microphone, so use speaker mode. Some phone brands silence the microphone during calls.
- Auto call recording must be turned ON again after the phone restarts.
