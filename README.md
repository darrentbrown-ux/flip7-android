# Flip 7 — Android

Full Flip 7 card game for Android 16+. Built with Kotlin + WebView wrapping the existing HTML5/JS game engine.

## Requirements
- Android 8.0+ (API 26), optimised for Android 16 (API 36)
- Landscape orientation

## Building
Open in Android Studio Ladybug (2024.2) or newer, or build from CLI:
```bash
./gradlew assembleDebug
```
APK output: `app/build/outputs/apk/debug/app-debug.apk`

## Architecture
The game is a standalone HTML5/JS application served from `assets/game/`. The Kotlin `MainActivity` hosts a full-screen WebView in immersive landscape mode with JavaScript enabled.
