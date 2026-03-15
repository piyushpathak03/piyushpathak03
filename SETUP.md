# 🚀 Setup Guide — Piyush Pathak GitHub Portfolio V3

## 📁 What's Inside

```
piyushpathak03_v3/
├── README.md                        ← Your live profile page
├── SETUP.md                         ← This file (keep local, no need to upload)
└── .github/
    └── workflows/
        └── snake.yml                ← Auto-generates contribution snake every 12h
```

---

## ⚡ Deploy in 3 Steps

### Step 1 — Create Profile Repository
1. Go to **https://github.com/new**
2. Name: **`piyushpathak03`** (must exactly match your username)
3. Visibility: **Public**
4. Do **NOT** initialise with README
5. Click **Create repository**

### Step 2 — Upload Files
**Option A: Web UI**
- Click "uploading an existing file" in the new repo
- Drag the entire `piyushpathak03_v3` folder contents (keep folder structure)
- Commit to `main`

**Option B: Git CLI**
```bash
cd piyushpathak03_v3
git init
git remote add origin https://github.com/piyushpathak03/piyushpathak03.git
git add .
git commit -m "🚀 Ultra premium portfolio V3"
git branch -M main
git push -u origin main
```

### Step 3 — Activate Snake Animation (2 min)
1. Repo → **Settings** → **Actions** → **General**
2. Under *Workflow permissions* → **Read and write permissions** → Save
3. Go to **Actions** tab → **Generate Contribution Snake** → **Run workflow**
4. Done — snake appears within 60 seconds ✅

---

## 🖼️ Dynamic Widgets Reference

| Widget | CDN | Auto-Updates |
|---|---|---|
| Header / Footer | `capsule-render.vercel.app` | Static render |
| Typing animations | `readme-typing-svg.demolab.com` | Static render |
| Skill icons grid | `skillicons.dev` | Static render |
| GitHub Stats card | `github-readme-stats.vercel.app` | Every few hours |
| Top Languages (donut) | `github-readme-stats.vercel.app` | Every few hours |
| Streak stats | `streak-stats.demolab.com` | Daily |
| Activity graph | `github-readme-activity-graph.vercel.app` | Daily |
| Trophy shelf | `github-profile-trophy.vercel.app` | Daily |
| Repo pin cards | `github-readme-stats.vercel.app` | Every few hours |
| Profile views counter | `komarev.com/ghpvc` | Real-time |
| Random quote card | `quotes-github-readme.vercel.app` | Each page load |
| Contribution snake | GitHub Actions → `output` branch | Every 12 hours |

> All widgets use your username `piyushpathak03` — no tokens, no secrets needed.

---

## ✅ Go-Live Checklist

- [ ] Repo named `piyushpathak03` created (Public)
- [ ] `README.md` uploaded to root
- [ ] `.github/workflows/snake.yml` uploaded (preserving folder path)
- [ ] Actions → Workflow permissions set to Read & Write
- [ ] Snake workflow triggered manually once
- [ ] Visit `github.com/piyushpathak03` — 🎉 live!
