# JEE PYQ CBT Practice  (made by DIVYANSH)

Static website - no Python packages, no build step.

## Files
- `index.html`  the whole app
- `lib/pdf.min.mjs`, `lib/pdf.worker.min.mjs`  PDF reader (keep the `lib` folder next to index.html)
- `server.py`, `requirements.txt`  only for hosts that want a start command (`python3 server.py`)

## Deploy (GitHub)
Upload this whole folder to a GitHub repository and deploy it as a static site
(GitHub Pages, or any host pointed at the repo). Open the site over https - it will not work
by double-clicking index.html (browsers block the PDF reader on file:// pages).

## Using it
1. (Returning) Step 1: load your progress file.
2. Step 2: add the Maths / Chemistry (/ Physics) PDF. Chapters, questions and the answer key are read automatically.
3. Step 3: pick chapters (all / first N / range a-b / random N per chapter), or question numbers, or PDF pages.
   Choose which questions may appear: New, Skipped, Wrong earlier, Correct earlier.
4. Step 4: timer + marking, Start. After the test, download the progress file.
