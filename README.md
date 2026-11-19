# AbIs — web version

AI fitness coach, built with Expo (React Native for web). This folder is the whole app as static files.

**Live:** https://<your-github-username>.github.io/abis/

## Deploy on GitHub Pages
1. Create a public repo named **`abis`** (the build expects this exact name).
2. Upload `index.html`, `404.html` and `.nojekyll` to the repo root.
3. Settings → Pages → Source: *Deploy from a branch* → Branch `main`, folder `/ (root)` → Save.
4. Open `https://<your-github-username>.github.io/abis/` after a minute or two.

`404.html` is a copy of `index.html` so links like `/abis/goal-body` still work after a refresh.
A different repo name needs a rebuild: `python3 build_github.py <repo-name>`.

## What works here
- Everything is saved in this browser (localStorage).
- Sign-in uses Supabase email codes; once signed in, data syncs and the AI features call the Supabase functions.
- Without sign-in (or if the Supabase project is paused), AI screens show demo results.

Font: Pretendard (SIL Open Font License 1.1). Exercise photos: Free Exercise DB (public domain).
