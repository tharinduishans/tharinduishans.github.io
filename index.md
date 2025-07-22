---
layout: default
title: Home
---

# Tharindu Ishan
## Embedded Systems Engineer

Passionate and skilled Embedded Systems Engineer with hands-on experience in sensor integration, power electronics, and real-time embedded control systems. Strong background in designing and developing industrial-grade hardware and firmware solutions, from schematic and PCB design to field deployment. Adept at bridging hardware and software for sensor-driven systems and automation platforms. Committed to delivering reliable, high-precision embedded products aligned with international manufacturing standards.

### 🚀 Expertise Areas
- **Programming Languages** - Python, C, C++, System Verilog, VHDL, Dart
- **Micro-controllers & Embedded Systems** - ARM Cortex-M (STM32), ESP32-S3/8266, PIC, AVR, Arduino, Raspberry Pi, NVIDIA Jetson, Qualcomm TurboX W5+ 
- **Autonomous Robotics** - ROS2 (SLAM, AMCL), FreeRTOS, Embedded Linux, Zephyr 
- **Communication Protocols** - UART, SPI, I2C, CAN, MODBUS, RS485, MQTT, HTTP, WebSockets, BLE, Calibration Protocols, Noise Analysis, Signal Conditioning
- **Hardware** - PCB Design (Altium Designer, Eagle, EasyEDA, Proteus), BLDC Motor Control, IMU, Lidar, Depth Cameras, PID, ESC design 
- **Machine Learning** - Object Detection (YOLO, MASK-RCNN), TensorFlow, OpenCV, Image Classification, Supervised Learning 
- **No-Code Automation** - n8n, Zapier, CI/CD pipelines, PM Tools (ClickUp, Trello)
- **Cloud & DevOps** - AWS (EC2, S3, RDS, Lambda), Docker, Kubernetes, Jenkins, Ansible, Terraform, Git, Monitoring (Prometheus/Grafana), Bash

### 🔥 Featured Projects

<div class="project-grid">
  {% for project in site.projects limit:3 %}
  <div class="project-card">
    <img src="{{ project.image }}" alt="{{ project.title }}">
    <h3><a href="{{ project.url }}">{{ project.title }}</a></h3>
    <p>{{ project.excerpt }}</p>
    <div class="tech-tags">
      {% for tech in project.technologies %}
      <span class="tag">{{ tech }}</span>
      {% endfor %}
    </div>
  </div>
  {% endfor %}
</div>

[View All Projects →](/projects)

### 📊 Quick Stats
- **4+ Years** of Engineering Experience
- **ROS2 Expert** in Autonomous Navigation, Robotic manipulation
- **Strong proficiency** in real-time systems, embedded Linux, and microcontroller programming
- **CI/CD implementation** with Jenkins, Docker, and AWS for streamlined DevOps workflows
- **10,000+** Devices Supported (Pet Tracking System)
- **AI integration** with machine learning models for face, voice, and emotion recognition
- **Automation workflows** using n8n, Zapier, and custom API integrations

---

## 📬 Contact {#contact}

**Email**: [wtiwijesinghe@gmail.com](mailto:wtiwijesinghe@gmail.com)  
**Phone**: +9471-4367-160  
**LinkedIn**: [tharindu-wijesinghe](https://linkedin.com/in/tharindu-wijesinghe)  
**Location**: Colombo, Sri Lanka

<style>
.project-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 2rem;
  margin: 2rem 0;
}

.project-card {
  border: 1px solid #e1e4e8;
  border-radius: 8px;
  padding: 1.5rem;
  transition: transform 0.2s;
}

.project-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 4px 12px rgba(0,0,0,0.1);
}

.project-card img {
  width: 100%;
  height: 200px;
  object-fit: cover;
  border-radius: 4px;
  margin-bottom: 1rem;
}

.tech-tags {
  margin-top: 1rem;
}

.tag {
  background: #f1f8ff;
  color: #0366d6;
  padding: 0.25rem 0.5rem;
  border-radius: 12px;
  font-size: 0.8rem;
  margin-right: 0.5rem;
  margin-bottom: 0.5rem;
  display: inline-block;
}
</style>
