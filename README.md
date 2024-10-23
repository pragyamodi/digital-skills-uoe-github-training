# Git Workshop: Hands-on Practice Repository

Welcome to our Git workshop! This repository is designed for hands-on practice with Git fundamentals. You can choose to follow along using either the Command Line Interface (CLI) or GitKraken based on your comfort level.

## 🎯 Workshop Flow

During this workshop, you'll:
1. Clone this repository
2. Switch to a training-specific branch
3. Create your own reflection file
4. Make your first commit
5. Push your changes

## 📝 Step-by-Step Instructions

Choose your preferred method:
- [Command Line Instructions](#command-line-instructions)
- [GitKraken Instructions](#gitkraken-instructions)

## Command Line Instructions

### 1. Clone the Repository
```bash
git clone [repository-url]
cd [repository-name]
```

### 2. Switch to Training Branch
```bash
# First, ensure you're up to date
git fetch origin

# Switch to the training branch (created by instructor)
git checkout training-DD-MM-YYYY
```

### 3. Create and Edit Your File
```bash
# Create your reflection file
touch reflections/reflection-XX.md   # Replace XX with your assigned number
```
Use your preferred text editor to add content to the file (template below).

### 4. Commit and Push Changes
```bash
# Check status of your changes
git status

# Stage your file
git add reflections/reflection-XX.md

# Commit your changes
git commit -m "Add reflection for participant XX"

# Push to remote repository
git push origin training-DD-MM-YYYY
```

## GitKraken Instructions

### 1. Clone the Repository
1. Open GitKraken
2. Click `File` → `Clone Repo`
3. Choose `Clone with URL`
4. Paste the repository URL
5. Choose where to save it on your computer
6. Click `Clone the repo!`

### 2. Switch to Training Branch
1. In the left panel, look for `remote/origin/training-DD-MM-YYYY`
2. Right-click on it and select `Checkout origin/training-DD-MM-YYYY`

### 3. Create and Edit Your File
1. Create a new file in the `reflections` folder named `reflection-XX.md` (replace XX with your assigned number)
2. Open it in your preferred text editor
3. Add content using the template below

### 4. Commit and Push Changes
1. In GitKraken, you'll see your new file under `Unstaged Files`
2. Drag the file to `Staged Files` (or click the Stage File button)
3. Enter your commit message: "Add reflection for participant XX"
4. Click `Commit changes`
5. Click `Push` in the top toolbar

## 📝 Reflection File Template

Copy this template into your `reflection-XX.md` file:

```markdown
# Git Workshop Reflections

## About Me
- [ ] Complete beginner with Git
- [ ] Have used Git a few times
- [ ] Use Git regularly

## I Will Use Git For...
(List at least 3 ways you plan to use Git)
1. 
2. 
3. 

## Today I Learned...
(Share one key thing you learned today)


## I'm Curious About...
(Note down something about Git you'd like to explore further)
```

## 📁 Repository Structure
```
.
├── README.md
├── reflections/
│   └── reflection-XX.md (you'll create this)
└── .gitignore
```

## ⚡ Quick Reference Guide

### Command Line
```bash
git status                    # Check status
git branch                    # List branches
git checkout branch-name      # Switch branches
git add filename             # Stage changes
git commit -m "message"      # Commit changes
git push origin branch-name  # Push changes
```

### GitKraken
- View changes: Left panel under `WIP`
- Stage files: Drag to `Staged Files`
- Switch branches: Double-click branch name
- Push: Click `Push` button in top toolbar
- View history: Center graph view
- Resolve conflicts: Built-in merge tool

## 🚫 Common Issues & Solutions

### CLI Issues
- **Permission denied**: Ensure you're logged in with correct credentials
- **Branch not found**: Run `git fetch` first
- **Push rejected**: Pull latest changes with `git pull` first

### GitKraken Issues
- **Can't see repository**: Try refreshing with `Ctrl/Cmd + R`
- **Authentication failed**: Re-authenticate in Settings → Authentication
- **Can't push**: Ensure you're connected to remote (check top toolbar)

## 🎓 Workshop Objectives
By the end of this workshop, you will have practiced:
- Cloning a repository
- Working with branches
- Creating and editing files
- Making commits
- Pushing changes to a remote repository

---
*For technical support during the workshop, please ask your instructor.*
