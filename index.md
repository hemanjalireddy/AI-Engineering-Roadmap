---
layout: home
title: Home
---

# 🚀 AI Learning Roadmap

Welcome to my AI/ML learning journey! This site documents the resources I'm studying, my key takeaways, and practice notebooks for each topic.

## 📚 Learning Approach

For each topic, I:
1. **Study** from curated resources (courses, books, papers)
2. **Summarize** key concepts and insights
3. **Practice** with hands-on notebooks and projects
4. **Share** everything openly for others to learn from

## 🗺️ Roadmap Overview

<div class="roadmap-grid">
{% for topic in site.topics %}
  <div class="topic-card">
    <h3><a href="{{ topic.url }}">{{ topic.title }}</a></h3>
    <p>{{ topic.description }}</p>
    <span class="difficulty {{ topic.difficulty }}">{{ topic.difficulty | capitalize }}</span>
  </div>
{% endfor %}
</div>

## 🎯 Current Focus

I'm currently working on: **[FAISS]**

## 📊 Progress

- Topics Completed: {{ site.topics | where: "status", "completed" | size }}
- Topics In Progress: {{ site.topics | where: "status", "in-progress" | size }}
- Topics Planned: {{ site.topics | where: "status", "planned" | size }}

---

## 💡 Why Open Source?

I believe in learning in public and contributing to the community. Feel free to:
- Use these resources for your own learning
- Suggest improvements or additional resources
- Share your own learning journey

<a href="{{ site.github_username }}" class="github-button">View on GitHub</a>
