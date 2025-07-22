---
layout: default
title: Projects
---

# Projects Portfolio

A showcase of my engineering projects spanning autonomous robotics, IoT systems, and industrial automation.

---

## 🤖 Autonomous Systems

{% assign autonomous_projects = site.projects | where: "category", "autonomous" %}
{% for project in autonomous_projects %}
<div class="project-entry">
  <div class="project-image">
    <img src="{{ project.image }}" alt="{{ project.title }}">
  </div>
  <div class="project-details">
    <h3><a href="{{ project.url }}">{{ project.title }}</a></h3>
    <p class="project-period">{{ project.period }}</p>
    <p>{{ project.excerpt }}</p>
    <div class="tech-stack">
      {% for tech in project.technologies %}
      <span class="tech-tag">{{ tech }}</span>
      {% endfor %}
    </div>
    <a href="{{ project.url }}" class="btn">View Details →</a>
  </div>
</div>
{% endfor %}

---

## 🌐 IoT & Cloud Systems

{% assign iot_projects = site.projects | where: "category", "iot" %}
{% for project in iot_projects %}
<div class="project-entry">
  <div class="project-image">
    <img src="{{ project.image }}" alt="{{ project.title }}">
  </div>
  <div class="project-details">
    <h3><a href="{{ project.url }}">{{ project.title }}</a></h3>
    <p class="project-period">{{ project.period }}</p>
    <p>{{ project.excerpt }}</p>
    <div class="tech-stack">
      {% for tech in project.technologies %}
      <span class="tech-tag">{{ tech }}</span>
      {% endfor %}
    </div>
    <a href="{{ project.url }}" class="btn">View Details →</a>
  </div>
</div>
{% endfor %}

---

## 🏭 Industrial & Control Systems

{% assign industrial_projects = site.projects | where: "category", "industrial" %}
{% for project in industrial_projects %}
<div class="project-entry">
  <div class="project-image">
    <img src="{{ project.image }}" alt="{{ project.title }}">
  </div>
  <div class="project-details">
    <h3><a href="{{ project.url }}">{{ project.title }}</a></h3>
    <p class="project-period">{{ project.period }}</p>
    <p>{{ project.excerpt }}</p>
    <div class="tech-stack">
      {% for tech in project.technologies %}
      <span class="tech-tag">{{ tech }}</span>
      {% endfor %}
    </div>
    <a href="{{ project.url }}" class="btn">View Details →</a>
  </div>
</div>
{% endfor %}

<style>
.project-entry {
  display: flex;
  margin-bottom: 3rem;
  padding-bottom: 2rem;
  border-bottom: 1px solid #e1e4e8;
}

.project-image {
  flex: 0 0 300px;
  margin-right: 2rem;
}

.project-image img {
  width: 100%;
  height: 200px;
  object-fit: cover;
  border-radius: 8px;
}

.project-details {
  flex: 1;
}

.project-period {
  color: #586069;
  font-style: italic;
  margin: 0.5rem 0;
}

.tech-stack {
  margin: 1rem 0;
}

.tech-tag {
  background: #f1f8ff;
  color: #0366d6;
  padding: 0.25rem 0.5rem;
  border-radius: 12px;
  font-size: 0.8rem;
  margin-right: 0.5rem;
  margin-bottom: 0.5rem;
  display: inline-block;
}

.btn {
  background: #0366d6;
  color: white;
  padding: 0.5rem 1rem;
  text-decoration: none;
  border-radius: 6px;
  display: inline-block;
  margin-top: 1rem;
}

.btn:hover {
  background: #0256cc;
  color: white;
}

@media (max-width: 768px) {
  .project-entry {
    flex-direction: column;
  }
  
  .project-image {
    flex: none;
    margin-right: 0;
    margin-bottom: 1rem;
  }
}
</style>
