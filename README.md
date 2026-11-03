# Mixed Reality

An Android mixed-reality starter app using Jetpack Compose and [SceneView](https://github.com/sceneview/sceneview). The app includes MR, AR, and Object modes, with a GitHub Actions workflow that builds and uploads a debug APK named `Mixed-Reality.apk`.

## Build

Open this project in Android Studio or run `gradle :app:assembleDebug` with JDK 21 and Android SDK 37 installed. The APK is generated at `app/build/outputs/apk/debug/Mixed-Reality.apk`.

The AR modes use ARCore and require a supported Android device and camera permission. Object mode renders a simple sample 3D scene.
