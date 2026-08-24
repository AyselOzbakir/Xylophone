# Xylophone

A simple iOS app that turns the screen into a playable xylophone — tap a colored key and it plays the corresponding note.

## Overview

The app displays a row of colored keys, each mapped to a musical note (C, D, E, F, G, A, B). Tapping a key plays its sound instantly, letting the user play simple tunes.

## Features

- Seven colored keys, one per musical note
- Instant audio playback on tap
- Simple, clean single-screen UI built with Auto Layout

## Requirements

- Xcode (latest stable recommended)
- iOS 13.0+
- Swift 5

## Getting Started

1. Clone the repository:
   ```bash
   git clone git@github.com:AyselOzbakir/Xylophone.git
   ```
2. Open `Xylophone.xcodeproj` in Xcode.
3. Select a simulator or a connected device.
4. Press **Run** (`Cmd + R`) to build and launch the app.

## Project Structure

```
Xylophone/
├── ViewController.swift    # Handles key taps and triggers sound playback
├── Main.storyboard         # UI layout for the keys
├── Assets.xcassets/        # App icons and key images
└── *.wav                   # Audio files for each note
```

## Acknowledgements

Built as part of the **App Brewery iOS App Development Bootcamp**.
