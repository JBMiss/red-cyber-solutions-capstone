# How to publish this repo on GitHub

This folder is ready to become a public GitHub repo. Here's the fastest path from zip-on-your-laptop to live repo.

## Option A — Web upload (no git install needed)

1. Go to https://github.com/new
2. **Repository name:** `red-cyber-solutions-capstone` (or similar — hyphens, no spaces)
3. **Description:** `Four-part security program design for a fictional cybersecurity consulting firm. B.S. Cybersecurity capstone work.`
4. **Public** ✓
5. **DO NOT** check "Add a README" or "Add a .gitignore" — this folder already has them
6. Click **Create repository**
7. On the new empty repo page, click **uploading an existing file** in the quick-setup block
8. Drag the entire contents of this folder (README.md, 01-risk-analysis/, 02-soc-migration/, etc.) into the uploader
9. Scroll down, set commit message to something like `Initial portfolio upload`, click **Commit changes**

Done. Your repo is live.

## Option B — Git command line

```bash
cd path/to/red-cyber-solutions-capstone
git init
git add .
git commit -m "Initial portfolio upload"
git branch -M main
git remote add origin https://github.com/JBMiss/red-cyber-solutions-capstone.git
git push -u origin main
```

## After it's live — make it a pinned repo

On your GitHub profile, click **Customize your pins** and select this repo. Pinned repos appear at the top of your profile, above everything else. This is what recruiters see first.

## Smart profile moves to make alongside this

1. **Add a short repo description** on GitHub (you'll be prompted). Copy from this repo's tagline: "A four-part security program design for a fictional cybersecurity consulting firm."

2. **Add topics** (GitHub's version of hashtags): `cybersecurity`, `penetration-testing`, `risk-analysis`, `security-operations`, `ethical-hacking`, `capstone`

3. **Link this repo from your LinkedIn profile** — under Projects, or as a featured post. Title it something like "Capstone: Security Program Design for a Consulting Firm" rather than "University of Phoenix Capstone" — recruiters respond better to project titles than course titles.

4. **Don't rename files.** The docx and pptx filenames match what's in the READMEs. If you rename them, the links break.

## What to do if you update the content later

Every file in this repo is editable in Word/PowerPoint. If you go back and tighten up a report, just replace the file in the folder and push again. The README stays the same because it describes the work, not the file.
