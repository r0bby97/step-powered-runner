# Step-Powered Runner

An Android exergame developed in Unity and C# for my bachelor's thesis. It combines a 3D endless runner with daily step counts: physical activity earns time to play.

## Features

- Lane-based running, jumping and swipe controls.
- Daily step counts converted into available playtime.
- Timed play and a walking-based play mode.
- Locally stored progress and high scores.

## Technology

- Unity **2021.3.24f1**, as recorded in `ProjectSettings/ProjectVersion.txt`.
- C# gameplay scripts and an Android build target.
- A fitness-data integration used to retrieve daily steps.

## Explore the project

- [Unity project](com.Company.JumpAndRun/)
- [Bachelor's thesis (PDF)](bachelorthesis_lange.pdf)
- [Original Android build (APK)](3D-Endless-Runner.apk)

## Open locally

1. Clone this repository and install Unity 2021.3.24f1 through Unity Hub, including Android Build Support if you want to build for Android.
2. Add `com.Company.JumpAndRun` as the project folder in Unity Hub.
3. Open `Assets/Scenes/menu.unity` and inspect the menu and gameplay scenes.
4. Before using step-based gameplay, configure the fitness-data integration in `Assets/MenuManager.cs` for your own test environment. The original project uses a personal endpoint; its service availability is not guaranteed.
5. Select Android in Unity's Build Settings to create a device build.

## Project status

This repository preserves an academic prototype and its original thesis materials. The Android build and external fitness integration have not been revalidated against current devices or services. Third-party models and other assets retain their original licenses.
