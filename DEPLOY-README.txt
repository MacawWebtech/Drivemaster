GITHUB PAGES DEPLOY (fixes 404)

1. Unzip this folder completely.
2. Upload ALL files from THIS folder to your GitHub repo ROOT.
   You must see index.html at the top level of the repo, not inside pages/.

   Correct:
     index.html
     about.html
     assets/
     ...

   Wrong (causes 404):
     DriveMaster/driving-school-template/pages/index.html

3. GitHub → Settings → Pages
   - Source: Deploy from a branch
   - Branch: main (or master)
   - Folder: / (root)
   - Save

4. Wait 1–2 minutes, then open:
   https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/

5. If repo is named YOUR-USERNAME.github.io, open:
   https://YOUR-USERNAME.github.io/
