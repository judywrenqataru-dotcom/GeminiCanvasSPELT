# Beyond the Chatbot: workshop website

Judy Wren · Qatar University · SPELT, 22 November 2026

## Before you upload: add two videos
Steps 2 and 3 were too large for me to download from Drive. Rename your files and put them in the `videos` folder:

| Your file in Drive | Rename to |
|---|---|
| Gemini Canvas 2 copy paste for canvas.mp4 | `videos/step2.mp4` |
| Gemini Canvas 3 Refining.mp4 | `videos/step3.mp4` |

(`step1.mp4` and `step4.mp4` are already there.)

## Publish on GitHub Pages
1. On github.com, click **New repository**. Name it, for example `gemini-canvas-workshop`, and make it **Public**.
2. Click **uploading an existing file**, then drag in everything inside this folder (`index.html`, `images`, `videos`, `README.md`). Click **Commit changes**.
3. Go to **Settings → Pages**. Under *Branch*, choose **main** and **/ (root)**, then **Save**.
4. After a minute or two, your site is live at `https://YOUR-USERNAME.github.io/gemini-canvas-workshop/`.

## Easy edits
Open `index.html` in GitHub (pencil icon) and search for:
- `Demo app 2` / `Demo app 3`: change the app names and the descriptions under them.
- `const GAMES`: the prompt library.
- `const FIX`: the fix-it phrases.
- `const CHECKS`: the checklist.
- `const IDEAS`: the classroom ideas.
