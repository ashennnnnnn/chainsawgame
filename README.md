# Bunny Chainsaw

A small static browser game. All game artwork is stored in `assets/` and loaded automatically—there are no sprite upload controls.

## Run locally
Keep the `index.html` file beside the `assets` folder, then open `index.html` in a modern browser. For best results, use GitHub Pages or a local static server.

## Publish with GitHub Pages
1. Create a new GitHub repository (for example, `bunny-chainsaw`).
2. Upload `index.html` and the entire `assets/` folder to the repository root.
3. In **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
4. Wait for the Pages URL to appear and open it.

The game fetches these files using relative paths:
- `assets/hero.png`
- `assets/zombie.png`
- `assets/max-zombie.png`
- `assets/room.png`
- `assets/winner-screen.png`

## Controls
- `A` / `D` or arrow keys: move
- `Space`: jump
- Chainsaw attacks automatically at close range

The 33-kill milestone changes the zombies and chiptune; reaching 50 kills shows the supplied congratulations artwork.
