# XR-I-Beam-Assignment
A lightweight VR demo built in Unity 6 for Oculus Quest that allows users to grab and move a realistic I-Beam using hand controllers.

---

## 🎯 Features

- Grab and move a scaled I-Beam (5 feet length, 5 inches width)
- Works on Oculus Quest / Quest 2 / Quest Pro
- Physics-based interaction using XR Toolkit
- XR Rig setup with left/right controller support
- Built with Unity XR Interaction Toolkit (Device-based input)

---

## 📦 Installation

Download and install the APK on your Oculus Quest using SideQuest:

1. Download SideQuest: https://sidequestvr.com/setup-howto  
2. Enable Developer Mode on your Quest  
3. Connect headset to PC via USB  
4. Drag and drop `interactive-beam-vr.apk` into SideQuest  
5. In headset → Apps → Unknown Sources → Launch the app

---

## 🕹️ Controls

| Action        | Input                         |
|---------------|-------------------------------|
| Grab Beam     | Grip or Trigger               |
| Release Beam  | Let go of grip/trigger        |
| Move/Rotate   | Move your hand normally       |

---

## 🗂️ Project Structure
Assets/
├── BeamModel/ # Imported I-Beam prefab/model
├── XR/ # XR Origin Rig & Interaction Manager
├── Scenes/
│ └── MainScene.unity

---

## 📋 Requirements

- Unity 6.x
- XR Interaction Toolkit (device-based)
- Android Build Support
- Oculus XR Plugin

---

## 📧 Developer Info

Developed by: Ahmed Waleed 
For demo/testing purposes only.
