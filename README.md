# Flutter TensorFlow Speech


The TensorFlow [audio recognition tutorial](https://github.com/tensorflow/docs/blob/master/site/en/r1/tutorials/sequences/audio_recognition.md), for use in flutter.

```dart
var speech = TfSpeech();
await for (var result in speech.stream) {
  print(result);
}
```