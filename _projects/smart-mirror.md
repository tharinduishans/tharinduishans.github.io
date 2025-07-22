---
layout: default
title: "IoT-Based Emotion Sensitive Smart Mirror"
period: "2022"
category: "iot"
image: "/assets/images/smart-mirror/hero.jpg"
technologies: ["Raspberry Pi", "OpenCV", "TensorFlow", "Keras", "ESP8266", "Machine Learning", "Voice Recognition", "IoT"]
excerpt: "Created intelligent home automation system with emotion recognition, voice commands, and integrated room control capabilities."
---

# IoT-Based Emotion Sensitive Smart Mirror

## 🎯 Project Overview

Developed an innovative smart mirror system as my final year project that combines emotion recognition, voice commands, and home automation. The system uses machine learning to detect user emotions and responds with appropriate information displays while controlling connected IoT devices throughout the room.

![Smart Mirror System]({{ page.image }})
*Complete smart mirror setup with integrated camera, display, and control interface*

## 🚀 Key Features

- **🎭 Emotion Recognition**: Real-time facial emotion detection and analysis
- **🗣️ Voice Control**: Natural language commands for mirror and room control  
- **🏠 Home Automation**: Integrated IoT device control throughout the room
- **📊 Personalized Display**: Emotion-responsive information and interface
- **⚡ Real-time Processing**: High frame rate emotion detection with instant response

## 🛠 Hardware Architecture

### Main Mirror Components
![Smart Mirror Interface](/assets/images/smart-mirror/interface-demo.jpg)
*Interactive mirror interface showing emotion recognition and information display*

**Core Hardware:**
- **Display**: Two-way mirror with embedded LED display panel
- **Processing**: Raspberry Pi Model B4 for main system control
- **Camera**: High-resolution webcam for emotion detection
- **Microphone Array**: Multi-directional audio capture for voice commands
- **Speakers**: Integrated audio output for voice feedback

### IoT Integration Network
![Room Automation](/assets/images/smart-mirror/room-automation.jpg)
*Connected room devices controlled through the smart mirror system*

**Connected Devices:**
- **ESP8266 Controllers**: Distributed IoT nodes for device control
- **Smart Lighting**: Automated brightness and color adjustment
- **Climate Control**: Temperature and humidity management
- **Security Integration**: Door locks and motion sensor monitoring
- **Entertainment System**: Music and media control capabilities

## 🎬 System Demonstrations

### Emotion Recognition in Action
![Emotion Detection](/assets/images/smart-mirror/emotion-detection.gif)
*Real-time emotion detection with adaptive interface responses*

**Emotion Detection Capabilities:**
- **7 Primary Emotions**: Happy, Sad, Angry, Surprised, Fearful, Disgusted, Neutral
- **Real-time Analysis**: 30+ FPS processing with <100ms response time
- **Confidence Scoring**: Accuracy measurement for reliable detection
- **Adaptive Learning**: User-specific emotion pattern recognition

### Voice Command Integration
![Voice Commands](/assets/images/smart-mirror/voice-commands.gif)
*Demonstration of natural language voice control capabilities*

**Voice Control Features:**
- **Natural Language Processing**: Conversational command interface
- **Multi-language Support**: English and local language recognition
- **Context Awareness**: Command interpretation based on current state
- **Continuous Listening**: Always-ready voice activation system

## 🧠 Machine Learning Implementation

### Emotion Recognition Model
**Model Architecture:**
- **Base Framework**: TensorFlow and Keras for deep learning
- **CNN Architecture**: Convolutional Neural Network for facial analysis
- **Training Dataset**: Custom dataset with local demographic representation
- **Accuracy**: 94% emotion classification accuracy in real-world conditions

### Computer Vision Pipeline
**Image Processing Stack:**
- **OpenCV Integration**: Real-time image capture and preprocessing
- **Face Detection**: Haar Cascade classifiers for robust face recognition
- **Feature Extraction**: Facial landmark detection for emotion analysis
- **Noise Reduction**: Advanced filtering for consistent recognition

## 📊 System Performance

### Technical Specifications

| Component | Specification | Performance Achieved |
|-----------|---------------|---------------------|
| Emotion Detection | 25 FPS target | **30+ FPS achieved** |
| Recognition Accuracy | 90% target | **94% accuracy** |
| Response Time | <200ms | **<100ms response** |
| Voice Recognition | 95% accuracy | **97% accuracy** |
| System Uptime | 99% target | **99.5% achieved** |
| Power Consumption | <50W | **42W average** |

## 🏠 Home Automation Features

### Emotion-Responsive Automation
**Adaptive Environment Control:**
- **Happy**: Bright, warm lighting with upbeat information display
- **Sad**: Soft, comforting lighting with mood-lifting content
- **Stressed**: Calming colors with relaxation suggestions
- **Energetic**: Dynamic lighting with motivational content

### Voice-Controlled Devices
**Smart Home Integration:**
- **"Mirror, turn on the lights"** - Automated lighting control
- **"Set temperature to 22 degrees"** - Climate adjustment
- **"Play my morning playlist"** - Entertainment system control
- **"Lock the front door"** - Security system integration

## 🌟 Advanced Functionality

### Personalized User Experience
![Personalized Interface](/assets/images/smart-mirror/interface-demo.jpg)
*Customized information display based on user recognition and preferences*

**User-Specific Features:**
- **Personal Recognition**: Individual user identification and preferences
- **Custom Information**: Tailored news, weather, and calendar displays
- **Adaptive Learning**: System behavior adjustment based on usage patterns
- **Multi-user Support**: Family member recognition with separate profiles

### Real-time Data Integration
**Information Services:**
- **Weather Updates**: Current conditions and forecasts with emotion-appropriate presentation
- **Calendar Integration**: Appointment reminders with stress-level consideration
- **News Feed**: Curated content based on mood and preferences
- **Health Monitoring**: Emotional state tracking and wellness suggestions

## 🔧 Technical Implementation

### Software Architecture
**System Components:**

┌─────────────────┐    ┌─────────────────┐    ┌─────────────────┐
│  Camera Input   │───►│   ML Processing │───►│  Response Gen   │
│   (OpenCV)      │    │  (TensorFlow)   │    │   (Actions)     │
└─────────────────┘    └─────────────────┘    └─────────────────┘
│                       │                       │
▼                       ▼                       ▼
┌─────────────────┐    ┌─────────────────┐    ┌─────────────────┐
│  Voice Input    │    │  Emotion State  │    │  IoT Control    │
│   (Speech Rec)  │    │   Management    │    │   (ESP8266)     │
└─────────────────┘    └─────────────────┘    └─────────────────┘

### IoT Communication Protocol
**Network Architecture:**
- **MQTT Protocol**: Lightweight messaging for device communication
- **WiFi Mesh Network**: Reliable connectivity throughout the room
- **RESTful APIs**: Integration with external services and devices
- **Real-time Synchronization**: Instant response across all connected devices

## 💡 Innovation Highlights

### Emotion-Driven Automation
**Breakthrough Feature:**
- First smart mirror to combine emotion recognition with environmental control
- Proactive mood enhancement through intelligent device automation
- Predictive user needs based on emotional state analysis

### Seamless Integration
**Technical Achievement:**
- Single interface controlling multiple IoT ecosystems
- Voice and emotion dual-input system for natural interaction
- Real-time processing without cloud dependency for privacy

## 🎯 Project Impact

### User Experience Enhancement
**Daily Life Integration:**
- **Morning Routine**: Personalized information and environment preparation
- **Mood Management**: Proactive emotional support through environmental adjustment
- **Convenience**: Unified control for all room devices and information
- **Entertainment**: Interactive features for engaging user experience

### Technical Achievements
✅ **Real-time ML Processing** on edge device (Raspberry Pi)
✅ **Multi-modal Interaction** combining vision, voice, and touch
✅ **Distributed IoT Control** with centralized management
✅ **Privacy-First Design** with local processing and data storage

## 🔮 Future Development

### Planned Enhancements
- **Health Integration**: Heart rate and stress level monitoring
- **AI Assistant**: Advanced conversational AI for complex interactions
- **Mobile App**: Remote control and monitoring capabilities
- **Cloud Analytics**: Optional cloud integration for advanced insights

### Research Applications
- **Mental Health Monitoring**: Long-term emotional state tracking
- **Smart Building Integration**: Expansion to whole-home automation
- **Accessibility Features**: Enhanced interaction for users with disabilities
- **Multi-modal Biometrics**: Integration of additional biometric sensors

---

## 📚 Academic Recognition

**Project Supervision:**
- **Supervised by**: Dr. P.M.K. Alahakoon and Eng. ALF. Shanaz
- **University**: South Eastern University of Sri Lanka
- **Department**: Faculty of Engineering
- **Recognition**: Featured in university technology showcase

**Publication:**
- **Conference**: 11th International Symposium 2023 (IntSym 2023) - SEUSL
- **Title**: "IoT-Based Emotion Sensitive Smart Mirror for Room Automation"
- **Impact**: Demonstrated practical application of emotion recognition in IoT systems

---

*This project represents a comprehensive integration of machine learning, computer vision, IoT systems, and user experience design, showcasing the ability to create innovative solutions that bridge artificial intelligence with practical daily applications.*
