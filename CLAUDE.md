# Claude Context for SharePad Project

## Environment
- **Device**: Android phone
- **Interface**: Claude app in Claude Code mode
- **Repository**: GitHub repo for creating simple one-page websites

## Project Purpose
This repository is designed for quickly creating simple, single-page websites for various purposes (event planning, trip options, information sharing, etc.). Each page should be:
- Simple and clean
- Mobile-friendly (primary viewing device is Android phone)
- Easy to share via link
- Self-contained (minimal external dependencies)

## GitHub Pages Setup

### What is GitHub Pages?
GitHub Pages lets you host static websites directly from your GitHub repository for free.

### Setup Options

**Option 1: Repository GitHub Pages** (Recommended for this project)
- Any repository can serve a website
- Enable in Settings → Pages
- Can serve from:
  - `main` branch root directory
  - `main` branch `/docs` folder
  - `gh-pages` branch
- URL format: `https://username.github.io/sharepad/`

**Option 2: User Site** (Separate repo needed)
- Create a special repository named `username.github.io`
- Automatically serves from main branch
- URL: `https://username.github.io/`
- Good for a main portfolio/hub site

### Current Setup
This repo (sharepad) should use **Option 1** - repository pages serving from the main branch root or a `/docs` folder.

## Workflow for Creating New Pages

1. **Describe the content** - Share what you want on the page (or upload a PDF/document)
2. **Claude creates the HTML** - A self-contained, mobile-friendly HTML file
3. **Test locally** - Review the generated page
4. **Commit and push** - Upload to GitHub on feature branch
5. **Access via GitHub Pages** - View at the live URL

## File Organization Suggestions

```
sharepad/
├── CLAUDE.md (this file)
├── README.md (project overview)
├── index.html (landing page/hub)
└── pages/
    ├── mexico-trip.html
    ├── birthday-party.html
    └── ...
```

Or simpler, flat structure:
```
sharepad/
├── CLAUDE.md
├── README.md
├── index.html
├── mexico-trip.html
└── ...
```

## Current Project
Creating a webpage for family day trip options in Mexico (converting from PDF).

## Tips for Future Chats
- Start with: "Please reference CLAUDE.md"
- Specify if you have content ready or need help structuring it
- Mention if you want to create a new page or update existing
- Remember: optimizing for mobile viewing on Android
