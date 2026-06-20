# GitHub Setup Guide

---

## Objectives
By completing this guide, contributors should be able to:
- Create a GitHub account
- Configure Git locally
- Clone repositories
- Create branches
- Commit changes
- Push changes
- Create Pull Requests

---

## Installation

### Install Git
- Verify installation:
  ```bash
  git --version
  ```
Configure Git
Set your username and email:

```bash
git config --global user.name "Your Name"
git config --global user.email "your-email@example.com"
```
Generate SSH Key
Run:

```bash
ssh-keygen -t ed25519 -C "your-email@example.com"
```
Add the public key to GitHub.

Git Workflow
Issue

↓

Branch

↓

Commit

↓

Push

↓

Pull Request

↓

Review

↓

Merge

Branch Naming
feature/issue-101-new-feature

bugfix/issue-102-fix-bug

docs/update-readme

Pull Request Rules
Small changes preferred

Link issue number

Update documentation when needed

Resolve review comments before merge
