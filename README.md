# Duplicate File Finder Utility

A simple offline desktop app that finds duplicate files and helps you safely clean extra copies.

## What it does

- Finds duplicate files inside a folder you choose
- Scans subfolders automatically
- Groups matching files together so they are easy to review
- Protects one copy in every duplicate group
- Marks extra copies for cleanup
- Moves extra copies to a safe folder before using Trash
- Moves extra copies to your system Trash after you review and confirm
- Shows Activity History after real move/Trash actions
- Lets you copy or clear Activity History
- Keeps history locally in `history.json`

## How to use it

1. Select a folder
2. Click Scan Folder
3. Review duplicate groups
4. Keep Preview Only enabled first
5. Move extra copies to the safe folder
6. Move extras to system Trash later only if you are sure
7. Review Activity History to see what happened

## Safety notes

- Files stay local
- Nothing is uploaded
- One copy is protected in every duplicate group
- Preview mode is enabled by default
- Moving to the safe folder is safest for review
- System Trash actions can usually be restored later
- Activity History stays local in `history.json`

The safe folder is named `Duplicate_Finder_Trash` and is created inside the selected folder when you choose to move extra copies.

## How to run locally

Python 3 is required.

```bash
cd ~/Desktop/MICRO SAAS/duplicate-file-finder
python3 main.py
```

No third-party packages are required.

## Screenshots

Add screenshots for Gumroad, itch, and GitHub here:

- `screenshots/main-window.png`
- `screenshots/scan-results.png`
- `screenshots/activity-history.png`

## Gumroad / itch

- Gumroad: TODO
- itch.io: TODO
