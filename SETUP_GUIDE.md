# Scientific Calculator - GitHub Setup Guide

## 📦 What's Ready

Your project structure is complete:
```
scientific-calculator/
├── .gitignore              # Excludes .class files and IDE files
├── README.md               # Full project documentation
└── calculator/             # Source code package
    ├── Main.java
    ├── CalculatorGUI.java
    ├── CalculatorEngine.java
    ├── Operation.java
    ├── ArithmeticOperation.java
    ├── TrigonometricOperation.java
    ├── LogarithmicOperation.java
    ├── ExponentialOperation.java
    └── SpecialOperation.java
```

## 🚀 How to Push to GitHub

### Step 1: Create GitHub Repository

1. Go to https://github.com/new
2. Repository name: `scientific-calculator`
3. Description: "A feature-rich scientific calculator built with Java Swing"
4. Make it **Public** (so it shows on your profile)
5. **Don't** initialize with README (we already have one)
6. Click "Create repository"

### Step 2: Push Your Code

Open terminal in the `scientific-calculator` folder and run:

```bash
# Initialize git
git init

# Add all files
git add .

# Commit
git commit -m "Initial commit: Scientific Calculator with GUI"

# Add remote (replace YOUR_USERNAME with your GitHub username)
git remote add origin https://github.com/YOUR_USERNAME/scientific-calculator.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 3: Add Topics/Tags (Optional but Recommended)

On your GitHub repository page:
1. Click "⚙️ Settings" (or the gear icon near "About")
2. Add topics: `java`, `swing`, `calculator`, `gui`, `scientific-calculator`, `oop`

## ✅ Done!

Your repository is now live! The README will automatically display on the repository homepage.

## 📝 Don't Forget

Before pushing, update the README.md:
- Replace `YOUR_USERNAME` with your actual GitHub username (lines 60, 198)

---

Ready to add your next project? 🎯
