# MOE Studio iPhone PWA (based on V0.4)

## Deploy with GitHub Pages
1. Create a **public** GitHub repository, e.g. `moe-studio`.
2. Upload the **contents of this folder** to the repository root (index.html, manifest.webmanifest, service-worker.js, icons/).
3. In repository Settings > Pages, set **Deploy from a branch**, branch **main**, folder **/(root)**, and Save.
4. Open `https://YOUR-USERNAME.github.io/moe-studio/` in iPhone Safari.
5. Share > Add to Home Screen > Add.

## Important limitations
This extends the existing V0.4 editor. Export remains WebM and may not work in iOS Safari; this is not yet a native iOS app or complete CapCut replacement. Offline caching covers app files, not uploaded media. Project JSON may not embed uploaded media. Avoid uploading private media to a public GitHub repository; import media within the app instead.
