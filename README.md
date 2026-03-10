# Bricktris 🧱

Bricktris is a browser-based, Tetris-inspired wall‑building game styled with 3:1 brick textures and a subtle background logo.  
It runs entirely in the browser using a single `index.html` file and image/audio assets.

## Play

- **Move piece**: `←` `→`  
- **Soft drop**: `↓`  
- **Rotate**: `↑`  
- **Hard drop**: `Space`  
- **Pause / Resume**: `P`  
- **Restart**: click **Start / Restart** button

Clear full horizontal rows to build a clean brick wall and increase your score.  
The game saves your **best score** in the browser using `localStorage`.

## Project Structure

```text
Bricktris/
├── index.html              # Main Bricktris game (HTML + CSS + JS)
├── bricktris.html          # Optional copy/variant of the game (not required for GitHub Pages)
├── assets/
│   ├── klinker_logo_white.png  # Faint background logo shown behind the playfield
│   ├── formback_1.png          # Brick texture 1
│   ├── formback_2.png          # Brick texture 2
│   ├── formback_3.png          # Brick texture 3
│   ├── formback_4.png          # Brick texture 4
│   ├── line_clear.wav (optional, you provide)   # Fun line‑clear sound
│   └── game_over.wav  (optional, you provide)   # Dramatic game‑over sound
└── README.md
```

## Running the Game Locally

1. Open the folder `Bricktris` on your computer.
2. Double‑click `index.html` to open it in your browser (Chrome, Edge, Firefox, etc.).
3. Start playing: click **Start / Restart** and use the keyboard controls above.

No build step or server is required; everything is pure HTML + JavaScript.

## GitHub Pages Deployment

1. Push this folder to your GitHub repository, for example `Sarah-klinker/bricktris`.
2. Ensure the repo has:
   - `index.html` at the root.
   - An `assets/` folder with all images and any sound files you want to use.
3. In GitHub, go to **Settings → Pages** and:
   - Select **Source**: `main` branch.
   - Select **Folder**: `/ (root)`.
4. After GitHub builds the site, open the provided URL to play Bricktris online.

## Visual & Audio Effects

Bricktris includes:

- Brick textures and a subtle grayscale background logo.
- Ghost piece preview, line‑clear particle bursts, row flash, and screen shake.
- A dramatic game‑over cinematic with Czech message: **“KONEC, zkus to znovu!”**.
- Optional sounds (`line_clear.wav`, `game_over.wav`) that you can customise.

To change visuals or behaviour, edit `index.html` directly—HTML, CSS, and JS are all in one file.

