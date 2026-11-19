# AbIs — web version

AI fitness coach, built with Expo (React Native for web). This folder is the whole app as static files.

**Live:** https://jijonjames.github.io/abis/

## Deploy on GitHub Pages
1. Repo named **`abis`** (the build expects this exact name).
2. Upload `index.html`, `404.html` and `.nojekyll` to the repo root.
3. Settings → Pages → Source: *Deploy from a branch* → Branch `main`, folder `/ (root)` → Save.

`404.html` is a copy of `index.html` so links like `/abis/goal-body` still work after a refresh.

## Sign-in
Email link: enter your email in the app, then open the link in the email — it brings you back here signed in.
Supabase must list `https://jijonjames.github.io/abis/` as the Site URL (Authentication → URL Configuration).

Font: Pretendard (SIL Open Font License 1.1). Exercise photos: Free Exercise DB (public domain).
