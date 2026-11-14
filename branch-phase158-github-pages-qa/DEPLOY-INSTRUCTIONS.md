# Branch Phase 158 QA deployment

Upload `qa-phase158/index.html` to the `Rmorris1177/branch-capacity-demo` repository on the `main` branch without replacing root `index.html`.

GitHub web UI: open repository > Add file > Upload files. GitHub's browser uploader may not preserve the folder when uploading a single file. Safest: create the folder `qa-phase158` using Add file > Create new file named `qa-phase158/README.md`, commit, then open folder and upload `index.html` there. Alternatively use GitHub Desktop to copy this directory into your cloned repository, commit and push.

Expected URL after Pages deployment: https://rmorris1177.github.io/branch-capacity-demo/qa-phase158/

IMPORTANT: GitHub Pages paths on the same domain SHARE localStorage and IndexedDB. For QA use a dedicated fresh Edge/Chrome browser profile, never the profile used for the existing demo. Do not import real data. This is a PUBLIC demo; use fictional records only.

After deployment, verify the URL actually loads and the + New project button works.

The original Phase 158 HTML is copied byte-for-byte. No fixes have been made.
