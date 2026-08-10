# Chore Wars v13 — GitHub Pages

A static single-file classroom game for Grade 4 / A1+ English: chores + Present Simple.

## Upload to GitHub Pages
Upload these items to the repository root:
- `index.html`
- `assets/`
- `.nojekyll`

No build step and no server are required.

## Teacher controls
- BACK / NEXT: free slide navigation for checking any mission.
- SCORES: manual +1 / -1 for each player and reset.
- TURN: move the active player manually.
- MUSIC / SFX: independent audio toggles.
- FULLSCREEN: presentation mode.
- Keyboard: Left/Right arrows = navigation, S = scores, M = music.

Mission completion is separate from navigation. `NEXT PROMPT` never closes a mission.

Progress is saved automatically in localStorage; the title screen offers CONTINUE when saved progress exists.
