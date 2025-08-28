# 🚀 Serkan Kızılırmak - Personal Portfolio Website

Welcome to my personal portfolio website! This is a fully dynamic, data-driven portfolio showcasing my journey as a Data Scientist.

**🔗 Visit my portfolio:** [Serkankizilirmak](https://serkankizilirmak.github.io/Serkankizilirmak/)

*Please note: This page is currently being updated. For the most current and accurate information, please visit my [resume](https://drive.google.com/file/d/1HqNyBmhV7Ccu5bZR03t-fs36jS01MS84/view?usp=sharing)) *

## 📬 Connect With Me

- **💼 LinkedIn**: [linkedin.com/in/serkankizilirmak](https://www.linkedin.com/in/serkankizilirmak/)
- **📧 Email**: serkankizilirmaak@gmail.com
- **🐙 GitHub**: [github.com/Serkankizilirmak](https://github.com/Serkankizilirmak)
- **📝 Medium**: [@serkankizilirmak](https://medium.com/@serkankizilirmak)

## 📖 About This Portfolio

This portfolio website represents more than just a showcase of my work—it's a **dynamic learning hub** where I document my professional journey, share valuable resources, and track my learning progress. The website is designed to be:

- **🔄 Easy to Update**: Simply edit JSON-like data files to update content
- **📚 Resource Sharing**: A personally curated collection of articles, papers, and learning materials that I've found insightful and saved for my own future reference, as well as for others.
- **🎯 Progress Tracking**: Interactive roadmap showing my learning journey
- **🤝 Open Source**: Available for others to fork and customize

## 💡 Why I Built This

I built this platform with a clear mission: to create a central hub for my professional work, continuous learning. It is designed to:

1. **📈 Professional Showcase**: Showcase my projects and practical experience.
2. **📖 Knowledge Sharing**: Share valuable resources, research papers, and articles I've discovered
3. **🎓 Learning Documentation**: Track my progress.
4. **💪 Motivation**: Maintain a public commitment to my professional growth and continuous learning.

The **Resources section** is particularly close to my heart—it contains carefully curated articles, research papers, and learning materials that have deepened my understanding of AI, data science etc.

## 🗂️ Structure

```
website/
├── 📊 data/                     # Data Layer
│   ├── data.js                  # Main portfolio data (experience, projects, skills, etc.)
│   └── resources-data.js        # Learning roadmap & curated articles
├── 📜 scripts/                  # JavaScript
│   ├── home-script.js           # Homepage animations & interactions
│   ├── page-script.js           # General page functionality
│   └── resources-script.js      # Resources page logic (roadmap, articles)
├── 🖼️ images/                   # Profile photos & visual assets
├── 🎨 styles.css                # Complete styling
├── 🏠 HTML Pages
│   ├── index.html               # Homepage
│   ├── about.html               # About me
│   ├── experience.html          # Professional experience
│   ├── projects.html            # Projects portfolio
│   ├── skills.html              # Skills accordion
│   ├── resources.html           # Learning roadmap & article collection
│   └── contact.html             # Contact information
└── 📖 README.md                 # You are here!
```

## ⚡ Key Features

### 🔄 Fully Dynamic Content
- **No hardcoded content**: Everything loads from `data/` files
- **Easy updates**: Change data files, see instant results
- **Consistent design**: Automated styling across all pages

## 🚀 How to Use This Template

### For Your Own Portfolio:

1. **🍴 Fork this repository**
2. **📝 Edit the data files**:
   - `data/data.js` - Update with your information
   - `data/resources-data.js` - Add your learning resources
3. **🖼️ Replace images** in the `images/` folder
4. **🚀 Deploy** to GitHub Pages or your preferred platform

### Key Files to Customize:

#### `data/data.js` - Your Professional Information
```javascript
const resumeData = {
    contact: { /* Your contact details */ },
    about: { /* Bio, services, quick facts */ },
    professionalExperience: [ /* Your work history */ ],
    projects: [ /* Your projects */ ],
    skills: [ /* Your skills */ ]
};
```

#### `data/resources-data.js` - Your Learning Journey
```javascript
const resourcesData = {
    roadmap: [ /* Your learning goals */ ],
    articles: [ /* Papers & articles you recommend */ ]
};
```

## 🤝 Contributing

Found this helpful? Here's how you can contribute:

1. **⭐ Star this repository** if you found it useful
2. **🍴 Fork it** for your own portfolio
3. **🐛 Report issues** or suggest improvements
4. **📚 Share resources** - suggest articles or papers

---

**💡 Feel free to fork, customize, and make it your own!**
