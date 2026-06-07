# Marathon Planner App

A static, browser-based marathon planning app.

## Features

- Weekly zero-to-marathon training plan
- June 2027 marathon target
- Weekly weight goals from 110 kg to 87 kg
- User-entered weight and height
- Calorie targets calculated from user inputs
- Food tab with recipe cards
- Full recipe popups
- Weekly shopping lists
- Favourite recipes
- Never Again recipe hiding
- CSV export
- JSON backup/restore
- Local browser storage only

## How to run locally

Open `index.html` in a browser.

No build step, server, database, or npm install is required.

## How to upload to GitHub

### Option 1: Upload through GitHub website

1. Create a new GitHub repository.
2. Upload `index.html`, `README.md`, and `.gitignore`.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, choose:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
5. Save.
6. GitHub will publish the app as a GitHub Pages site.

### Option 2: Use git

```bash
git init
git add .
git commit -m "Initial marathon planner app"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
git push -u origin main
```

Then enable GitHub Pages in repository settings.

## Data storage

The app stores edits, favourites, hidden recipes, profile inputs, and notes in browser `localStorage`.

Use **Download backup** before clearing browser data or moving to another computer.

## Medical note

This app is for personal planning only. It does not replace medical advice, especially for electrolyte issues or medical conditions.
