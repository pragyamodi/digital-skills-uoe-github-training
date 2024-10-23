# Git Commit Message Guide

A good commit message is crucial for maintaining a clear project history. This guide will help you write better commit messages.

## 💡 The Golden Rules

1. Keep the first line (subject) under 50 characters
2. Start with a capital letter
3. Don't end with a period
4. Use imperative mood ("Add" not "Added" or "Adds")
5. Add a blank line between subject and body
6. Wrap the body at 72 characters

## 📝 Commit Message Structure

```
Subject line (What you did in 50 chars or less)

Body text (Detailed explanation of why and how)
- List impact of changes
- Explain side effects
- Reference related issues/tickets
```

## ✅ Good vs ❌ Bad Examples

### Good Examples:
```
Add user authentication feature
```
```
Fix navigation bar overflow on mobile devices
```
```
Update documentation for API endpoints

- Add new endpoints for user management
- Include request/response examples
- Fix outdated deployment instructions
```

### Bad Examples:
```
fixed stuff              # Too vague
```
```
Added new feature...     # Uses past tense, ends with ...
```
```
i updated the docs      # Doesn't start with capital, too informal
```

## 🎯 Common Use Cases

### Feature Addition
```
Add [feature name]

- What the feature does
- Why it was added
- How to use it
```

### Bug Fixes
```
Fix [brief description of bug]

- What was causing the bug
- How it was fixed
- How to verify the fix
```

### Documentation
```
Update documentation for [topic]

- What was changed
- Why it needed updating
- What sections were affected
```

### Refactoring
```
Refactor [component/function name]

- What was refactored
- Why it needed refactoring
- Impact on existing functionality
```

## 🚀 Pro Tips

1. **Be Specific**
   - "Fix typo in login form" is better than "Fix typo"
   - "Add password reset feature" is better than "Add new feature"

2. **Reference Issues**
   - Include ticket/issue numbers: "Fix #123: Add password validation"
   - Link related issues: "Related to #456"

3. **Group Related Changes**
   - If you need to make multiple unrelated changes, make multiple commits
   - Each commit should be a single logical change

4. **Think About Future You**
   - Will you understand what this change was about in 6 months?
   - Will others understand your changes?

## 🎭 Commit Types

Use these prefixes to categorize your commits:
- `feat:` - New feature
- `fix:` - Bug fix
- `docs:` - Documentation changes
- `style:` - Formatting, missing semicolons, etc.
- `refactor:` - Code restructuring
- `test:` - Adding tests
- `chore:` - Maintenance tasks

## ❓ When to Commit

- After completing a logical change
- When you want to save your progress
- Before switching tasks
- When your changes are testable
- Small, frequent commits are better than large, infrequent ones
