# GlassQR

A minimalist Android QR scanner app built with CameraX and ML Kit.

## Features
- Fast QR detection using ML Kit Barcode Scanning.
- Minimalist camera-only UI.
- Target Android 15 (SDK 35), Min SDK 28.

## Getting Started

### 1. Open in Android Studio
1. Launch Android Studio.
2. Select **Open** and navigate to the `GlassQR` folder.
3. Wait for the Gradle sync to complete.

### 2. Connect Device/Emulator
1. Connect a physical Android device via USB (ensure USB Debugging is on).
2. Or start an Android Emulator from the Device Manager.

### 3. Build and Run
1. Click the **Run** button (green play icon) in the toolbar.
2. Select your device and click **OK**.
3. Grant camera permissions when prompted.
4. Point the camera at a QR code to scan.

## Architecture
- **CameraX**: For handling camera lifecycle and preview.
- **ML Kit**: For fast and reliable QR code detection.
- **Jetpack Compose**: For a modern UI implementation.
