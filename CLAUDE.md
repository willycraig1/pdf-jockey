# PDF Jockey

A single-file HTML app for visually merging and reorganizing PDFs and images, as a light stand-in for Acrobat. `index.html` is the app. `README.md` lists every feature.

## Rules
- Files never leave the machine: no uploads, server or accounts.
- Keep it one self-contained HTML file.
- Destructive actions (delete, export) keep their visual warnings, like the red hover on delete and the ghost on duplicate.
- Respect page rotation embedded by scanners, and include manual rotation in aspect-ratio math. Both were past bugs.
- `Summary.rtf` is a private note and is gitignored.

## Run
Open `index.html` in a browser. Remote: github.com/willycraig1/pdf-jockey.
