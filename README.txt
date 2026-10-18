GUITAR SONGBOOK — GITHUB PAGES (IPHONE-FRIENDLY)

Structure:
  index.html         Website (dark theme, alphabetical sorting, autoscroll)
  songs.json         Short index of all songs
  songs/             One JSON file per song (19 placeholders included)

Publish from your phone:
1. Create a public GitHub repository in Safari.
2. Upload index.html and songs.json to the repository ROOT.
3. Upload all JSON files inside a folder named songs/ (preserve that folder path).
4. Repository Settings > Pages > Deploy from a branch > main > /(root) > Save.
5. Open https://YOUR-USERNAME.github.io/YOUR-REPO/

Add a song:
1. Create songs/new-song.json by copying another song file, then edit its id, title, and details.
2. Add an entry to songs.json with id, title and file: songs/new-song.json.
3. Commit both changes. The website sorts alphabetically AUTOMATICALLY; the JSON entries do not need to be sorted.

How to enter lyrics and chords in each file:
  "lines": [
    "[G]Your own lyrics [D]go here",
    "[Em]Next line of your [C]arrangement"
  ]
Chord labels in square brackets are displayed above the following lyrics.
The placeholder files intentionally have empty lyric lines; no copyrighted song lyrics are included.

Scroll speed: slider is seconds per approximate lyric line (0.1 to 5).
GitHub Pages is public; do not commit passwords or private information.
When previewing, use your GitHub Pages URL instead of opening index.html directly from Files, because fetch() needs an HTTP website.
