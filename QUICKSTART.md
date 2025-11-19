# Quick Start Guide

## Step 1: Upload to GitHub

1. Create a new repository on GitHub named `ai-roadmap` (or any name you prefer)
2. Make it **Public**
3. Upload all these files to the repository

## Step 2: Customize Your Site

### Update `_config.yml`
```yaml
title: AI Learning Roadmap
author: Your Name
email: your.email@example.com
github_username: yourusername
```

### Update `index.md`
- Change the "Current Focus" section
- Personalize the introduction

## Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** → **Pages**
3. Under "Source", select `main` branch
4. Click **Save**
5. Your site will be live at: `https://yourusername.github.io/ai-roadmap`

## Step 4: Add Your First Topic

1. Look at the example files in `_topics/`
2. Copy `01-ml-fundamentals.md` as a template
3. Create a new file like `03-your-topic.md`
4. Fill in your resources, notes, and notebooks

## Step 5: Add Your Notebooks

### Option A: GitHub
1. Create a `notebooks/` folder in your repo
2. Upload your `.ipynb` files
3. Link them in your topic file

### Option B: Google Colab
1. Save your notebook to Google Drive
2. Share it publicly
3. Get the Colab link and add it to your topic

### Option C: Kaggle
1. Create a Kaggle notebook
2. Make it public
3. Add the Kaggle link to your topic

## Example Topic Entry

```yaml
notebooks:
  - title: "Linear Regression Implementation"
    description: Building linear regression from scratch
    github_link: https://github.com/yourusername/ai-roadmap/blob/main/notebooks/linear_reg.ipynb
    colab_link: https://colab.research.google.com/drive/your-notebook-id
```

## Need Help?

- Check out the [Jekyll documentation](https://jekyllrb.com/docs/)
- Look at the example topics for reference
- Test locally with `bundle exec jekyll serve`

Happy learning! 🚀
