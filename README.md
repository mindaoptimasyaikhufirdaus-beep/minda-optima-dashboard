# Minda Optima 2 — Pantas Baca Daily Monitoring Dashboard

Professional dashboard untuk monitoring Meta Ads account Minda Optima 2, dengan automatic daily data refresh via Claude.

## Setup Instructions

### Step 1: Create GitHub Repository

1. Go to **https://github.com/new**
2. Repository name: `minda-optima-dashboard` (atau nama lain)
3. Description: `Minda Optima 2 - Pantas Baca Daily Monitoring Dashboard`
4. Choose: **Public** (so team boleh access via URL)
5. Click **Create repository**

### Step 2: Upload Files to GitHub

**Option A: Via Web (Simplest)**

1. Go to your new repo
2. Click **Add file → Upload files**
3. Drag and drop:
   - `dashboard.html`
   - `data.json`
4. Click **Commit changes**

**Option B: Via Git Command Line (Advanced)**

```bash
git clone https://github.com/[your-username]/minda-optima-dashboard.git
cd minda-optima-dashboard
# Copy dashboard.html and data.json into this folder
git add .
git commit -m "Initial commit: dashboard setup"
git push
```

### Step 3: Enable GitHub Pages

1. Go to repo → **Settings**
2. Scroll to **Pages** (left sidebar)
3. Under "Source", select **main** branch
4. Click **Save**
5. Wait 1-2 min, refresh page
6. You'll see: `Your site is published at https://[username].github.io/minda-optima-dashboard/`

### Step 4: Access Dashboard

Your dashboard is now live at:
```
https://[your-username].github.io/minda-optima-dashboard/
```

Share this link with your team!

---

## Daily Data Updates

**How it works:**
- Claude Scheduled Task runs daily at 6 AM (MYT)
- Pulls latest data from Meta Ads account via MCP
- Updates `data.json` in your GitHub repo
- Dashboard auto-fetches newest data

**To setup automation:**
1. Come back and tell me repo URL
2. I'll create Claude Scheduled Task
3. Done ✅

---

## Local Testing

To test locally before pushing to GitHub:

1. Open `dashboard.html` in browser (double-click)
2. Dashboard should load with current data
3. Check all sections, buttons, remarks work

---

## Troubleshooting

**Dashboard shows blank?**
- Check browser console (F12)
- Make sure `data.json` is in same folder as `dashboard.html`
- Refresh page

**GitHub Pages not working?**
- Wait 2-3 minutes after enabling Pages
- Check Settings → Pages to confirm publish status
- Try incognito browser window

---

## File Structure

```
minda-optima-dashboard/
├── dashboard.html        # Main dashboard (fetches data.json)
├── data.json            # Current data (updated daily)
└── README.md            # This file
```

---

## Support

Questions? Let me know.

---

**Last Updated:** 2026-09-19
