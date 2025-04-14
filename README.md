# 📝 Commit Convention

## 🔍 Overview

This document outlines our project's commit message conventions. Following these guidelines ensures a clean, readable, and organized git history that makes it easier to:

- 📊 Track changes
- 📚 Understand project history
- 🔄 Generate changelogs automatically
- 🏷️ Identify important changes at a glance

## 📋 Commit Message Format

```
<type>(<scope>): <subject>
```

### ✨ Header

The header is mandatory and has a special format that includes a **type**, an optional **scope**, and a **subject**:

- **type**: Identifies the kind of change
- **scope**: (Optional) Specifies the section of the codebase affected
- **subject**: A concise description of the change

#### 🔖 Types

- **feat**: A new feature
- **fix**: A bug fix
- **refactor**: A code change that neither fixes a bug nor adds a feature
- **chore**: Other changes that don't modify src or test files
- **revert**: Reverts a previous commit

#### 🔬 Scope

The scope provides additional contextual information about the area of the change:

- **task**: The task number at hand.

Examples: `feat(L5-304):`, `fix(OOL-003):`, `docs(2SS-87654):`

#### 📄 Subject

The subject is a short description of the change:

- Use the imperative, present tense: "add" not "added" nor "adds"
- Don't capitalize the first letter
- No period (.) at the end
- Keep it under 50 characters

## 💡 Examples

### ✨ Feature Addition

```
feat(OOL-003): add email verification workflow
```

### 🐛 Bug Fix

```
fix(L5-4506): resolve incorrect tax calculation
```

## 🌟 Best Practices

1. **Write meaningful commits**: Each commit should represent a single logical change
2. **Commit early and often**: Small, focused commits are easier to understand
3. **Don't commit half-done work**: Use git's staging area
4. **Test before committing**: Make sure your code passes all tests
5. **Write good commit messages**: Follow the format described above

## 📖 Additional Resources

- [Conventional Commits](https://www.conventionalcommits.org/)
- [Angular Commit Message Guidelines](https://github.com/angular/angular/blob/master/CONTRIBUTING.md#commit)
- [How to Write a Git Commit Message](https://chris.beams.io/posts/git-commit/)
