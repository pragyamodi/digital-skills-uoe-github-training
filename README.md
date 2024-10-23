# Git Workshop: Hands-on Practice Repository

Welcome to our Git workshop! This repository is designed for hands-on practice with Git fundamentals. You can choose to follow along using either the Command Line Interface (CLI) or GitKraken.

## 🎯 Repository Structure
```
.
├── README.md (this file)
├── training_log/
│   ├── README.md (reflection guidelines)
│   ├── YYYY-MM-DD/ (training session folders)
│   └── templates/
│       └── participant-template.md
├── resources/
│   ├── commit-message-guide.md
│   └── workflow-guidelines.md
└── .gitignore
```

## 📝 Workshop Flow

1. Clone this repository
2. Switch to today's training branch
3. Create your reflection file using [this template](training_log/templates/participant-template.md)
4. Add your thoughts (2-3 minutes)
5. Commit and push your changes

## 🛠️ Instructions

### Using Command Line (CLI)

```bash
# 1. Clone the repository
git clone [repository-url]
cd [repository-name]

# 2. Switch to training branch
git fetch origin
git checkout training-DD-MM-YYYY

# 3. Create and edit your reflection
# Copy template content from training_log/templates/participant-template.md
# Create your file in training_log/YYYY-MM-DD/participantXX.md

# 4. Add and commit
git add training_log/YYYY-MM-DD/participantXX.md
git commit -m "Add reflection for participant XX"

# 5. Push changes
git push origin training-DD-MM-YYYY
```

### Using GitKraken

1. **Clone Repository**
   - Open GitKraken → File → Clone Repo
   - Enter repository URL and choose local path
   - Click "Clone the repo!"

2. **Switch Branch**
   - Find and checkout `training-DD-MM-YYYY`

3. **Create Your Reflection**
   - Copy template from training_log/templates/participant-template.md
   - Create new file: training_log/YYYY-MM-DD/participantXX.md
   - Fill out the template

4. **Commit & Push**
   - Stage changes (drag to Staged Files)
   - Write commit message
   - Click "Commit changes" then "Push"

## ⚡ Quick Reference

### Essential Git Commands
```bash
git status          # Check current state
git branch          # List branches
git checkout NAME   # Switch branches
git add FILE       # Stage changes
git commit -m ""   # Commit changes
git push           # Share changes
```

### Common Issues

**CLI Users**
- Permission denied → Check credentials
- Branch not found → Run git fetch
- Push rejected → Pull latest changes

**GitKraken Users**
- Repository not visible → Refresh (Ctrl/Cmd + R)
- Auth failed → Check Settings → Authentication
- Push failing → Verify remote connection

## 🎓 Workshop Goals
- Create your first Git repository
- Learn basic Git commands
- Practice the Git workflow
- Collaborate using Git
- Understand branches and commits

## 📌 Additional Resources
- Detailed reflection guidelines: [training_log/README.md](training_log/README.md)
- Commit message guide: [resources/commit-message-guide.md](resources/commit-message-guide.md)
- Workflow guidelines: [resources/workflow-guidelines.md](resources/workflow-guidelines.md)

---
*Need help? Ask your instructor!*
