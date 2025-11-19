# How to Add a New Topic

## Step 1: Create a Folder

Create a new folder for your topic:
```
your-topic-name/
```

## Step 2: Add README.md in the Folder

Create a `README.md` file inside your topic folder with this structure:

```markdown
# Your Topic Name

**Status:** 🟡 In Progress / 🟢 Completed / ⚪ Planned  
**Started:** Month Year

## 📖 Overview

Brief description of what this topic covers.

## 📚 Resources

### Courses
- [Course Name](link) - Brief description, what you learned

### Books
- Book Title by Author - Your notes

### Articles & Videos
- [Article/Video Title](link) - Key takeaways

## 📓 Notebooks

- [Notebook Name](./notebooks/notebook_name.ipynb) - What this notebook covers

## 🎯 Key Concepts Learned

- ✅ Concept 1
- ✅ Concept 2
- 🟡 Concept 3 (in progress)

## 💡 Important Insights

Your personal insights and aha moments.

## 📊 Projects

1. **Project Name** - What you built and learned

## 🔗 Additional Resources

Links to other helpful resources

---

[← Back to Main Roadmap](../README.md)
```

## Step 3: Create notebooks Folder

Inside your topic folder, create a `notebooks/` folder:
```
your-topic-name/
  ├── README.md
  └── notebooks/
      ├── notebook1.ipynb
      └── notebook2.ipynb
```

## Step 4: Update Main README

Add your topic to the main README.md in the Topics section:

```markdown
## 📚 Topics

### 1. Your Topic Name
**Status:** 🟡 In Progress  
[📖 View Resources & Notes](./your-topic-name/)
```

## Example Structure

```
ai-roadmap/
├── README.md
├── machine-learning-basics/
│   ├── README.md
│   └── notebooks/
│       ├── linear-regression.ipynb
│       └── logistic-regression.ipynb
├── deep-learning/
│   ├── README.md
│   └── notebooks/
│       └── neural-networks.ipynb
└── nlp/
    ├── README.md
    └── notebooks/
        └── sentiment-analysis.ipynb
```

## Tips

- Use clear, descriptive folder names (lowercase with hyphens)
- Keep your README.md organized and updated
- Link to your notebooks from the README
- Add screenshots or outputs from notebooks when relevant
- Update the main README whenever you add a new topic
