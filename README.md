# CTC Trading Card Collection

This repository is the source library for the CTC teacher trading-card project.

## Before uploading teacher photos
**This repository is currently public.** Change it to **Private** before adding teacher/staff photos or other personal information. In GitHub: Settings → Danger Zone → Change repository visibility → Private.

## How to add a teacher
1. Put the teacher's photo in `teacher-photos/`.
2. Use a simple filename, preferably lowercase with hyphens, e.g. `mrs-haythe.jpg`.
3. Copy `teacher-record-template.md` into `teacher-records/` and rename it to match the photo, e.g. `mrs-haythe.md`.
4. Fill in the teacher's name, subject, card type, artwork style, and stat level.
5. Commit the photo and record to GitHub.

When you want a card, tell ChatGPT: **"Make the card for [teacher name] from my CTC trading cards repo."** ChatGPT can look up the matching record and photo through the connected GitHub integration, then create the card in the conversation. Generated card images are not automatically committed to this repository; ask separately if you want a card file saved here.

## Required card choices
- Card type: Basic, GX, or EX
- Artwork: Full Art or Regular Art
- Stats: Max, High, Regular, or Low

## Folders
- `teacher-photos/` — original reference photos
- `teacher-records/` — one metadata file per teacher
- `completed-cards/` — finished card images you choose to archive
- `ctc-branding/` — CTC logo, card-back reference, and design assets

## Privacy
Keep this repository private while it contains identifiable teacher/staff photos. Only upload images you have permission to use for this project.
