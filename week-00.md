# Week 0: Setup

## What I did
- Installed WSL + Ubuntu 26.04, set up Git and an SSH key, first push

## Problem I hit (fixed with the help of clauade)
- `wsl` failed with "Class not registered" (WSL was half installed)
- Fix: reinstalled WSL with the official installer, turned on
  Virtual Machine Platform (`wsl --install --no-distribution`), restarted

## Commands I learned
- `wsl --list --verbose`: shows installed Linux systems
- `ssh-keygen -t ed25519`: creates an SSH key
- `git add` → `git commit` → `git push`
 
