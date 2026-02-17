# Git Workflow Documentation

## Step 1: Initialize Repository

git init
git add .
git commit -m "Initial commit"

## Step 2: Create Branches

git checkout -b dev
git checkout -b feature/add-feature

## Step 3: Merge Workflow

feature → dev → main using Pull Requests

## Step 4: Create Tag

git tag -a v1.0 -m "Version 1.0 release"
git push origin v1.0

## Concepts Practiced

- Branching Strategy
- Pull Requests
- Merge
- Conflict Resolution
- Version Tagging
