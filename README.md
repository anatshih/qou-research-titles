# Two Research Title Proposals

A one-page site that presents two candidate research titles to my supervisor,
with the model behind each one, the source studies, the data on the study
setting, the design decisions, and a linked reference list.

- Course: Organizational Culture and Leadership Capabilities
- Supervisor: Dr. Fares Mujahid
- Programme: PhD, Palestine Polytechnic University
- Author: Ahmad Natsheh

## What is in this folder

| File | What it is |
| --- | --- |
| `index.html` | The whole site. One file. All the styles and the script are inside it. |
| `.nojekyll` | Tells GitHub Pages to serve the files as they are. |
| `README.md` | This file. |

## Two ways to use it

**For the meeting, open it from the research folder.** Double-click
`index.html`. Every reference carries a **PDF in folder** link that opens the
paper itself from the `Papers/` folders one level up. Put the whole
`Research Papers - Two Titles` folder on a USB stick or in Drive, and the
supervisor can read every paper straight from the page.

**On the web, the publisher links do the work.** Upload only the three files in
this folder. The page notices it is not running from a folder and hides the
**PDF in folder** links by itself, so no reader ever sees a broken link. The
**Open access** links still open the full text for most of the papers.

**Do not upload the PDFs.** Edmondson (1999) is in *Administrative Science
Quarterly* and Bock et al. (2005) is in *MIS Quarterly*. Both are paywalled, and
putting them on a public page is republishing work that is not yours to
distribute. The page links to a free, legitimate copy of Edmondson at MIT and to
the journal page for Bock, which is the right way to give a reader access.

## How to put it on GitHub Pages

1. Make a new repository on GitHub. A good name is `qou-research-titles`.
2. Upload the three files in this folder to the root of the repository.
3. Open **Settings**, then **Pages** in the left menu.
4. Under **Source** choose **Deploy from a branch**.
5. Pick the `main` branch and the `/ (root)` folder, then press **Save**.
6. Wait about one minute. The page goes live at
   `https://<your-user-name>.github.io/<repository-name>/`

## Notes

- No build step and no server. Plain HTML, CSS and a small script.
- The two web fonts come from Google Fonts, so they need the internet. Without
  it the page falls back to the fonts on the computer and still reads well.
- The page is light or dark to match the reader's system setting.
- Print it from the browser for a clean PDF. Each title starts on its own page.
- In the two model diagrams, clicking any box shows that variable's scale, item
  count, reliability and source.

## One thing to settle before the meeting

The number of academic and administrative staff at Al-Quds Open University is
not published as a current official figure. The page says this openly and lists
what single studies report. Take the exact figure from the Human Resources
Department, then run the power analysis on it.
