# Bridgespace QR Scanner

A minimalist Android QR scanner built with CameraX, ML Kit, and Jetpack Compose.

The repository contains the current scanner implementation at the root and an earlier `GlassQR` implementation kept for comparison.

## Build

Open the root project in Android Studio with JDK 17 and Android SDK 35, then run:

```bash
./gradlew test assembleDebug
```

Camera permission is requested only when scanning. No scan history, account, analytics, or remote backend is included.

## License

MIT
