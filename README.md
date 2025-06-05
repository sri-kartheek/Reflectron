# Reflectron: An IoT-Based Smart Mirror

Reflectron is a smart mirror system that integrates IoT, health monitoring, facial recognition, and emotion detection to deliver real-time, personalized information to users. Built using a Raspberry Pi, Python, and multiple sensors, it aims to enhance daily well-being through intelligent, touchless interaction.

## 🧠 Key Features

- Real-time health monitoring (heart rate, SpO₂, body temperature)
- Facial and emotional recognition for personalized content
- Interactive GUI with real-time weather, news, and calendar updates
- Motivational quotes for mental well-being
- Built using open-source tools and Python libraries (OpenCV, Tkinter)
- Energy-efficient and modular design for easy upgrades

## 🛠️ Tech Stack

- **Hardware:** Raspberry Pi, MAX30100, IR Sensor, Ultrasonic Sensor, Pi Camera, 2-way mirror
- **Software:** Python, OpenCV, Tkinter, Sensor APIs
- **Protocols:** Local data processing with potential for cloud/remote extension

## ⚙️ System Architecture

The system uses a modular design where the Raspberry Pi collects and processes data from various sensors and a camera. Output is shown on an LCD behind a two-way mirror. User detection, emotion analysis, and health data are handled in real-time with personalized interactions.

## 💡 How It Works

1. User presence detected via IR/Ultrasonic sensors
2. Facial recognition & emotion detection with Pi Camera
3. Health metrics monitored via MAX30100 and temp sensor
4. GUI dynamically displays personalized information
5. Display powers off on inactivity for energy efficiency

## 📦 Folder Structure

```
Reflectron/
├── images/              # Snapshots of prototype
├── code/                # Python source files
├── docs/                # Project report and references
├── README.md
```

## 📽️ Demo

> Add GIFs or video links showing live demo here (if available)

## 🧪 Future Enhancements

- AI-based health predictions & alerts
- Voice assistant for hands-free use
- Cloud integration for remote access
- Augmented reality (AR) features
- Smart home automation support

## 📜 License

This project is licensed under the MIT License - see the LICENSE file for details.
