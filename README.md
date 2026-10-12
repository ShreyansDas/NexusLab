# NexusLab

A virtual science lab for **Class 9 Science** (NCERT *Exploration*, 2026): 13 chapters, each with study notes, 10 interactive simulations (many in 3D), quizzes with fresh questions every time, an AI doubt solver, and the textbook pages.

**Live site:** `https://<your-username>.github.io/<repository-name>/`

## Files

| File | What it is |
| --- | --- |
| `index.html` | The whole website: simulations, notes, quizzes, sign up / sign in |
| `ch00.pdf` – `ch13.pdf` | The textbook, one file per chapter (`ch00` = front pages), shown in the **Book** tab |
| `.nojekyll` | Tells GitHub Pages to serve the files as they are |

## Publish with GitHub Pages

1. Create a new repository on GitHub.
2. Click **Add file → Upload files**, drag in every file from this folder, and click **Commit changes**.
3. Open **Settings → Pages**. Under *Build and deployment*, choose **Deploy from a branch**, branch **main**, folder **/ (root)**, then **Save**.
4. After a minute or two the site is live at `https://<your-username>.github.io/<repository-name>/`.

## Notes

- Accounts made on the sign-up page are saved in each visitor's own browser, not on a server.
- Outside claude.ai, the doubt solver answers from the chapter notes (it cannot reach Claude without a server).
- An internet connection is needed for the fonts and the PDF reader.
