# Chess Puzzle Board

A single-page web app: set up chess puzzles (by hand, from FEN, or from a screenshot),
solve them with legal moves, comment each move and copy the line to send.

No build step — Vercel serves the files as they are.

## Deploy to Vercel

**Option 1 – GitHub (no tools needed)**
1. Create a new repository on github.com and upload all files in this folder.
2. On vercel.com choose *Add New… → Project*, import the repository and press *Deploy*
   (Framework preset: *Other*, no build command, output directory: root).

**Option 2 – Vercel CLI**
```
npm i -g vercel
cd chess-puzzle-board-vercel
vercel --prod
```
