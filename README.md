# Neon Trail

A glowing neon drawing canvas built entirely with Flutter's `CustomPainter`. Draw with your finger and the strokes light up with a layered neon glow.

📱 **[Download the APK](https://drive.google.com/file/d/1ku4S7IpZN7WLljhVbLmoapx187iEAfOS/view?usp=drive_link)**

https://github.com/user-attachments/assets/c138a88c-1b16-4f63-af7f-da7dfd29598d

<img src="https://github.com/user-attachments/assets/c629d2bd-1e28-43d7-bfbc-ea254b557b92" width="300" alt="Neon Trail screenshot">

## Features

- Smooth freehand drawing with gesture tracking
- Neon glow drawn with `MaskFilter.blur`, scaled to the stroke width
- Color picker for the trail color (`flutter_hsvcolor_picker`)
- Settings popup to customize strokes
- Undo and eraser mode

## How it works

Each stroke is painted in a `CustomPainter` as a blurred glow layer under a solid core line. Together they create the neon-tube look without shaders or images. Drawing state (lines, undo, erase) lives in a GetX view model.

## Tech stack

Flutter · Dart · `CustomPainter` · GetX · flutter_hsvcolor_picker

## Run it

```bash
git clone https://github.com/MuhammadUsamaProgrammer/neon-trail.git
cd neon-trail
flutter pub get
flutter run
```
