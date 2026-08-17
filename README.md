# 🎧 Audio Guided Virtual Reality for Finger Motor Skill Rehabilitation

**AGVRSystem** is a VR-based hand rehabilitation application built with **Unity 6 and Meta Quest**. It uses controller-free hand tracking and audio guidance to help users perform finger and hand motor exercises.

## 🎯 Features

* 🖐️ Controller-free hand tracking
* 🎧 Audio-guided exercises
* 📊 Real-time accuracy and grip tracking
* 🔄 Adaptive difficulty
* 💾 Session data storage
* 🌐 REST API integration
* 📱 Offline data backup
* 👋 Left and right hand support

## 🏋️ Rehabilitation Exercises

| Exercise           | Purpose             |
| ------------------ | ------------------- |
| Grip Hold          | Grip strength       |
| Precision Pinching | Fine motor control  |
| Finger Spreading   | Finger flexibility  |
| Finger Tapping     | Finger dexterity    |
| Thumb Opposition   | Finger coordination |

## 🛠️ Technology Stack

* **Engine:** Unity 6 (URP)
* **VR:** Meta Quest
* **SDK:** Meta XR SDK
* **Hand Tracking:** OVRHand / OVRSkeleton
* **XR:** OpenXR, XR Interaction Toolkit
* **Backend:** FastAPI (Python)
* **Data:** JSON + REST API
* **Audio:** Unity Audio + Offline Voice Clips

## 🔄 System Workflow

```text
Meta Quest
    ↓
Hand Tracking
    ↓
Exercise Detection
    ↓
Accuracy & Rep Calculation
    ↓
Audio + Visual Feedback
    ↓
Session Summary
    ↓
REST API / Offline Storage
```

## 🏗️ Main Scenes

1. **Main Menu** – Patient ID and session start
2. **Calibration** – Hand tracking setup
3. **Rehabilitation Session** – Five exercises and performance tracking

## 📊 Performance Tracking

The system records:

* Exercise accuracy
* Grip strength
* Completed repetitions
* Exercise duration
* Overall session performance

Difficulty is adjusted based on recent exercise accuracy.

## 🔊 Audio Guidance

The system provides voice instructions, encouragement, completion messages, and tracking-loss warnings. Pre-recorded audio clips provide offline support when TTS is unavailable.

## 🌐 Backend

A **FastAPI** server receives and stores rehabilitation session data through a REST API. If the server is unavailable, session data is saved locally and can be uploaded later.

## 🚀 Future Scope

* Therapist dashboard
* More rehabilitation exercises
* Gamification
* Multilingual voice guidance
* AI-based exercise coaching
* Biometric integration
* Remote rehabilitation support

## 📌 Project Status

**Prototype / Academic Project**

Built using Unity 6 and Meta Quest for VR-based finger motor rehabilitation.


<img width="1536" height="1024" alt="ChatGPT Image Jul 3, 2026, 06_01_03 AM" src="https://github.com/user-attachments/assets/ca1f4976-e232-4ef7-b8d4-c8ca6f48839d" /># VRPROJECT!
[Uploading ChatGPT Image Jul 3, 2026, 06_01_03 AM.png…]()
<img width="1536" height="1024" alt="ChatGPT Image Jul 3, 2026, 06_00_51 AM" src="https://github.com/user-attachments/assets/23ce8d26-44c2-4445-a644-2961df8d11b8" />
![Uploading Screenshot 2026-06-20 172548.png…]()
<img width="1190" height="477" alt="Screenshot 2026-06-22 004305" src="https://github.com/user-attachments/assets/651b648c-5d39-41ae-aa00-bee407db1ba2" />
![Uploading Screenshot 2026-06-22 004305.png…]()
<img width="1197" height="491" alt="Screenshot 2026-06-22 004454" src="https://github.com/user-attachments/assets/8b8d721d-055c-4388-9e49-57f59a7d33aa" />
<img width="1190" height="477" alt="Screenshot 2026-06-22 004305" src="https://github.com/user-attachments/assets/c8643943-a53a-4677-b1f0-6ca8090ab064" />
<img width="1197" height="491" alt="Screenshot 2026-06-22 004454" src="https://github.com/user-attachments/assets/9eca115d-e76a-45f9-b468-d140746c8709" />

<img width="841" height="472" alt="Screenshot 2026-06-20 172548" src="https://github.com/user-attachments/assets/2e952044-6c35-4d82-8ceb-823a7a43e627" />
<img width="1190" height="477" alt="Screenshot 2026-06-22 004305" src="https://github.com/user-attachments/assets/280b2877-afc5-4e3a-b6a7-d525f90de214" />
<img width="1197" height="491" alt="Screenshot 2026-06-22 004454" src="https://github.com/user-attachments/assets/43119a00-a32c-44b5-a57c-46a9bea49daf" />



