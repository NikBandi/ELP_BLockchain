# Git Workshop Guide

This document contains everything you need for the Git onboarding session.

---

## Step 1: Clone the Repository

Open your terminal and run:

git clone https://github.com/YOUR-REPO-URL
cd ELP_Blockchain

(Replace YOUR-REPO-URL before the workshop.)

---

## Step 2: Create Your Own Branch

Use your name in the branch title.

git checkout -b yourname-intro

Example:

git checkout -b bob-intro

---

## Step 3: Edit the Team Members File

Open this file:

00_onboarding/team_members.md

Add your name and 1–2 interests using this format:

- Name: Your Name | Interests: Interest 1, Interest 2

Save the file.

---

## Step 4: Stage and Commit Your Changes

git add 00_onboarding/team_members.md
git commit -m "Added yourname intro"

Example:

git commit -m "Add bob intro"

---

## Step 5: Push Your Branch to GitHub

git push origin yourname-intro

---

## Step 6: Open a Pull Request

1. Go to the GitHub repository.
2. Click “Compare & pull request.”
3. Fill out the Pull Request template completely.
4. Submit your PR.

---

## Important Rules

- Never commit directly to main.
- Always create a new branch.
- Always open a Pull Request.
- Use clear, descriptive commit messages.
- Pull the latest main before starting new work.

---

## If You Get an Error

Common fixes:

To check your branch:
git branch

To switch back to main:
git checkout main

To pull latest updates:
git pull origin main

If you are stuck, ask in the session.

---

you guys are geniuses you got it
