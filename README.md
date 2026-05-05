# Staycation Planner · May 2026

A personal day planner for May 5–17, 2026. Drag-and-drop daily block builder with end-of-day reflections. All data saves automatically to your browser's localStorage.

## Setup (GitHub Pages — ~5 minutes)

### 1. Create a new repo on GitHub
- Go to https://github.com/new
- Name it something like `staycation-planner`
- Set it to **Public** (required for free GitHub Pages)
- Don't initialize with a README
- Click **Create repository**

### 2. Push the file
Open your terminal and run:

```bash
cd staycation-planner
git init
git add index.html
git commit -m "init staycation planner"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/staycation-planner.git
git push -u origin main
```

Replace `YOUR_USERNAME` with your GitHub username.

### 3. Enable GitHub Pages
- Go to your repo on GitHub
- Click **Settings** → **Pages** (left sidebar)
- Under "Branch", select `main` and `/ (root)`
- Click **Save**
- Wait ~60 seconds, then your planner is live at:
  `https://YOUR_USERNAME.github.io/staycation-planner`

## Usage

- **Day Plan tab** — drag blocks from the left into your day, reorder by dragging, pick crossfit time, select work/todo items
- **Reflection tab** — end-of-day prompts: what went well, what didn't, carry forward, energy/mood, free notes
- **All Days tab** — overview of all 13 days, see which have plans or reflections
- **Date dots** in the header — blue = has plan, green = has reflection. Click to jump to any day.
- Everything auto-saves to localStorage as you type/interact.

## Notes

- Data lives in your browser's localStorage for the device you use it on. If you want to use it on multiple devices, just use one device consistently (or copy the localStorage data manually).
- Clearing browser data / site data will erase saved plans. Don't do that during your staycation!
