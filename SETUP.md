# 📦 GitHub Profile Portfolio — Setup Guide

This folder is your complete GitHub profile repository.

---

## 🚀 How to Upload

1. Go to **github.com/new** and create a repository named exactly: `piyushpathak03`
   - ✅ Make it **Public**
   - ✅ **Do NOT** initialize with a README (you already have one)

2. Upload the `README.md` file from this folder into that repository.

3. Visit `github.com/piyushpathak03` — your portfolio is live instantly!

---

## 🖼️ Dynamic Images — How They Work

All images in the README are **external CDN URLs** — they render live automatically on GitHub. No files needed.

| Widget | CDN Service | What It Shows |
|---|---|---|
| **Header / Footer Banner** | `capsule-render.vercel.app` | Animated waving gradient banner |
| **Typing Animation** | `readme-typing-svg.demolab.com` | Cycling role titles, animated |
| **GitHub Stats Card** | `github-readme-stats.vercel.app` | Stars, commits, PRs, issues |
| **Top Languages Card** | `github-readme-stats.vercel.app` | Your most-used languages |
| **Streak Stats** | `streak-stats.demolab.com` | Current streak, longest streak |
| **Activity Graph** | `github-readme-activity-graph.vercel.app` | Contribution heatmap graph |
| **Trophy Shelf** | `github-profile-trophy.vercel.app` | Auto-earned GitHub trophies |
| **Profile Views Counter** | `komarev.com/ghpvc` | Live visitor count badge |

> ✅ All widgets automatically use your username `piyushpathak03` — no token or login required.

---

## ✏️ How to Customise

### Change your typing lines
Find this block in `README.md`:
```
&lines=🤖+Generative+AI+Manager...
```
Edit the text after each `;` separator. Use `+` for spaces and encode special chars with `%XX`.

### Change banner text / colors
The `capsule-render` URL parameters:
- `text=` → your display name
- `desc=` → subtitle
- `customColorList=` → gradient preset (try 2, 3, 12, 24)

### Update project links
Replace the GitHub repo URLs in the **Featured Projects** section with your actual repo slugs.

---

## 📁 Folder Contents

```
piyushpathak03/
├── README.md        ← Upload this to your GitHub profile repo
└── SETUP.md         ← This guide (keep locally, don't need to upload)
```

---

## 🔒 No Tokens or Secrets Needed

All widgets are public CDN services — they pull your GitHub public data automatically.
No API keys, no GitHub Actions, no secrets required.
