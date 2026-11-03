# Mushaf Notes

Read and lightly annotate the Madinah Mushaf on phone, tablet or laptop. Works offline once installed. Notes stay on each device; use Menu → Save backup file to keep a copy.

## Publish with GitHub Pages

1. Create a new **public** repository, for example `mushaf`.
2. Add these files to it, keeping `index.html` at the top level of the repo:
   ```
   git clone https://github.com/YOUR-USERNAME/mushaf.git
   cd mushaf
   # copy the contents of this folder in here
   git add .
   git commit -m "Add Mushaf Notes"
   git push
   ```
3. In the repo, go to **Settings → Pages**. Under *Build and deployment*, set Source to **Deploy from a branch**, choose **main** and **/ (root)**, then Save.
4. After a minute or two the app is live at `https://YOUR-USERNAME.github.io/mushaf/`.

## Install on a phone

- **iPhone (Safari):** Share → Add to Home Screen.
- **Android (Chrome):** menu → Install app, or Menu → Install app inside Mushaf Notes.

Then open it from the home screen and tap **Menu → Save all pages for offline**.

## Updating

Change `index.html`, commit and push. Installed copies pick up the new version the next time they open online. The page images never need changing.
