---
layout: default
title: Home
---

# Tharindu Ishan
## Embedded Systems Engineer

Dedicated Electrical and Electronics Engineer with hands-on experience in smart device development, manufacturing processes, robotics applications and automation. Proven expertise in developing self-navigating systems and connected device platforms.

### 🚀 Expertise Areas
- **Autonomous Robotics** - ROS2, SLAM, Navigation Systems
- **Embedded Systems** - ARM Cortex-M, ESP32, Raspberry Pi
- **IoT & Cloud** - AWS, Docker, Jenkins, CI/CD Pipelines
- **Machine Learning** - Computer Vision, TensorFlow, OpenCV
- **Industrial Automation** - PLCs, Control Systems, SCADA

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
- **10,000+** Devices Supported (Pet Tracking System)
- **99.9%** System Uptime Achieved
- **ROS2 Expert** in Autonomous Navigation

---

## 📬 Contact {#contact}

**Email**: [wtiwijesinghe@gmail.com](mailto:wtiwijesinghe@gmail.com)  
**Phone**: +94 71 43 67 160  
**LinkedIn**: [tharindu-wijesinghe](https://linkedin.com/in/tharindu-wijesinghe)  
**Location**: Kegalle, Sri Lanka

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
