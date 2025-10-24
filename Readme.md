# CV - Alexandru Pascan

My personal CV, automatically built and deployed using GitHub Actions.

## 🔗 Live Site

**[alexandru.pascan.ro](https://alexandru.pascan.ro)**

## 📄 About

This repository contains my professional CV as a LaTeX source file that is automatically compiled to PDF and deployed to GitHub Pages.

## 🛠️ Tech Stack

- **LaTeX** - CV source format
- **GitHub Actions** - Automated building and deployment
- **GitHub Pages** - Hosting
- **HTML/CSS** - Web presentation layer

## 🚀 How It Works

1. CV is written in LaTeX (`sdet.tex`)
2. On push to `main`, GitHub Actions automatically:
   - Compiles the LaTeX to PDF
   - Deploys both PDF and HTML to GitHub Pages
3. Site is accessible at custom domain

## 📝 Structure

```
.
├── .github/
│   └── workflows/
│       └── build-cv.yml    # CI/CD pipeline
├── sdet.tex                # CV source (LaTeX)
├── index.html              # Web presentation
└── README.md
```

## 🔄 Updates

To update the CV:

1. Edit `sdet.tex`
2. Commit and push to `main`
3. GitHub Actions automatically rebuilds and deploys

## 📫 Contact

- Email: alexandru@pascan.ro
- GitHub: [@alpascan](https://github.com/alpascan)
