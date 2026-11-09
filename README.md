# Happy Birthday

A single-screen birthday card: a large greeting and a signature drawn over a background image.

Built while following Google's [Android Basics with Compose](https://developer.android.com/courses/android-basics-compose/course) course (the "Happy Birthday" codelab).

## Features

- Full-screen background image with semi-transparent overlay
- Greeting message and signature loaded from string resources

## Built with

- Kotlin, Jetpack Compose, Material 3
- `Box`, `Column`, `Image` and `Text` composables, `ContentScale.Crop`
- Compose `@Preview`
- Min SDK 24, target/compile SDK 35

## Run it

1. Open the project folder in Android Studio and let Gradle sync.
2. Run the `app` configuration on an emulator or device (Android 7.0 / API 24 or newer).

Or, with a device or emulator connected:

```sh
./gradlew installDebug
```
