# AI Learning Roadmap

My personal journey learning AI/ML, documented with resources, notes, and practice notebooks.

🌐 **Live Site**: [https://yourusername.github.io/ai-roadmap](https://yourusername.github.io/ai-roadmap)

## 📖 About

This repository contains:
- **Learning Resources**: Curated courses, books, papers, and tutorials
- **Study Notes**: Key concepts and insights from each topic
- **Practice Notebooks**: Hands-on Jupyter notebooks demonstrating concepts
- **Progress Tracking**: Visual roadmap of completed and planned topics

## 🚀 Quick Start

### Setting Up Your Own Roadmap

1. **Fork or clone this repository**
   ```bash
   git clone https://github.com/yourusername/ai-roadmap.git
   cd ai-roadmap
   ```

2. **Update the configuration**
   - Edit `_config.yml` with your name, email, and GitHub username
   - Update the site title and description

3. **Enable GitHub Pages**
   - Go to repository Settings → Pages
   - Set source to `main` branch
   - Your site will be live at `https://yourusername.github.io/ai-roadmap`

4. **Test locally (optional)**
   ```bash
   bundle install
   bundle exec jekyll serve
   ```
   Visit `http://localhost:4000` to preview

## 📝 Adding New Topics

Create a new file in `_topics/` folder (e.g., `03-nlp.md`):

```yaml
---
layout: topic
title: Natural Language Processing
description: Understanding and processing human language with ML
difficulty: intermediate
status: in-progress
date_started: 2025-02-01
order: 3

resources:
  - title: "NLP Course"
    type: Course
    link: https://example.com
    description: Brief description
    notes: |
      - Key takeaway 1
      - Key takeaway 2

notebooks:
  - title: "Sentiment Analysis"
    description: Building a sentiment classifier
    github_link: https://github.com/yourusername/ai-roadmap/blob/main/notebooks/sentiment.ipynb
    colab_link: https://colab.research.google.com/...
---

## Overview
Your content here...
```

## 📓 Adding Notebooks

1. **Create your notebook** (Jupyter, Colab, Kaggle)
2. **Upload to GitHub** in a `notebooks/` folder in this repo
3. **Link it in your topic file** using the `notebooks:` section
4. **Optional**: Add Colab and Kaggle links for easy access

### Example Notebook Structure
```
ai-roadmap/
├── notebooks/
│   ├── 01_linear_regression.ipynb
│   ├── 02_logistic_regression.ipynb
│   └── 03_neural_network.ipynb
```

## 🎨 Customization

- **Colors**: Edit CSS variables in `assets/css/style.scss`
- **Layout**: Modify `_layouts/topic.html`
- **Home page**: Edit `index.md`

## 📊 Topic Status

- `completed`: Finished studying and practicing
- `in-progress`: Currently working on
- `planned`: On the roadmap

## 🤝 Contributing

Found a great resource or spotted an error? Feel free to:
- Open an issue
- Submit a pull request
- Share your own learning journey

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

Thanks to the amazing AI/ML community for creating accessible learning resources!

---

**Note**: Remember to update the GitHub username and URLs throughout the repository!
