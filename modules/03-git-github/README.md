# Module 3: Git & GitHub Basics (1 Hour)

## Learning Objectives
By the end of this module, you'll be able to:
- Understand version control basics
- Use essential Git commands
- Create and manage GitHub repositories
- Collaborate using Git & GitHub

## Part 1: Git Basics (20 mins)

### 1. Initial Setup
```bash
# Configure Git
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"

# Start a new project
git init
```

### 2. Essential Git Commands
```bash
# Check status
git status

# Add files
git add filename.html
git add .  # Add all files

# Commit changes
git commit -m "Add initial website files"

# View history
git log
```

### 🔨 Exercise 1: Local Repository
1. Create a new folder for your website
2. Initialize Git
3. Add your HTML/CSS files
4. Make your first commit

## Part 2: GitHub (20 mins)

### 1. Repository Setup
```bash
# Create new repo on GitHub.com first, then:
git remote add origin https://github.com/username/repo-name.git
git branch -M main
git push -u origin main
```

### 2. Basic GitHub Workflow
```bash
# Pull changes
git pull origin main

# Push changes
git push origin main

# Clone repository
git clone https://github.com/username/repo-name.git
```

### 🔨 Exercise 2: GitHub Setup
1. Create a GitHub account (if needed)
2. Create a new repository
3. Push your local project
4. View it on GitHub.com

## Part 3: Branching & Collaboration (15 mins)

### 1. Working with Branches
```bash
# Create branch
git branch feature-name
git checkout feature-name
# or
git checkout -b feature-name

# Switch branches
git checkout main

# Merge branches
git merge feature-name
```

### 2. Collaboration Workflow
1. Fork repository
2. Clone your fork
3. Create feature branch
4. Make changes
5. Push to your fork
6. Create pull request

### 🔨 Exercise 3: Branching
1. Create a new branch
2. Add a new feature
3. Commit changes
4. Merge back to main

## Part 4: Best Practices (5 mins)
- Write clear commit messages
- Commit often
- Use meaningful branch names
- Keep repos organized
- Update regularly

## Common Git Commands Cheat Sheet
```bash
# Basic commands
git init                    # Start new repo
git status                  # Check status
git add .                   # Stage all changes
git commit -m "message"     # Commit changes
git push                    # Upload to GitHub
git pull                    # Download from GitHub

# Branching
git branch                  # List branches
git checkout -b branch-name # Create & switch branch
git merge branch-name       # Merge branches

# Information
git log                     # View history
git diff                    # View changes
```

## Resources
- [GitHub Guides](https://guides.github.com/)
- [Git Documentation](https://git-scm.com/doc)
- [GitHub Learning Lab](https://lab.github.com/)

## 🎯 Mini-Project
Create a team website:
1. Create repository
2. Add team members
3. Create feature branches
4. Make pull requests
5. Review & merge changes

## Next Steps
- Practice Git commands
- Explore advanced Git features
- Contribute to open source
- Move on to Module 4: Deployment! 