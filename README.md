# Android WaveRecorder _(android-waverecorder)_

[![standard-readme compliant](https://img.shields.io/badge/readme%20style-standard-brightgreen.svg?style=flat-square)](https://github.com/RichardLitt/standard-readme)

> Record Wav files in Android

Based off of http://www.edumobile.org/android/audio-recording-in-wav-format-in-android-programming/

## Install

 - Download AAR file from the [releases page](https://github.com/Sustenance/android-waverecorder/releases) or checkout from source.
 - [Follow latest instructions to add as a dependency in Android Studio](https://developer.android.com/studio/projects/android-library#AddDependency)
 
## Usage

For Android >= 6.0, make sure to [request app permissions](https://developer.android.com/training/permissions/requesting) at runtime.

```java
WaveRecorder waveRecorder = new WaveRecorder("DestinationFolderName");
waveRecorder.startRecording();
waveRecorder.stopRecording("fileName"); // Defaults to current timestamp
```

## Contributing

PRs welcome. 

If editing the Readme, please conform to the [standard-readme](https://github.com/RichardLitt/standard-readme) specification.

## License

MIT