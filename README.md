# Hydro Tower

An idle game where water flows down a tower of paddle wheels, turbines, sluice gates, whirlpools and jet flumes. 30 generated stages, each with its own name, signature label and description.

## Put it on GitHub Pages
1. New repo (e.g. `hydro-tower`). Upload `index.html`, `manifest.webmanifest`, `sw.js` and `icons/` (the `src/` folder is optional).
2. Settings → Pages → Deploy from branch → main / root.
3. Open `https://YOURNAME.github.io/hydro-tower/` on your phone. Install: iPhone Safari → Share → Add to Home Screen; Android Chrome → menu → Install app.

Saves are in the browser (localStorage). To push an update to installed copies, bump `V` in `sw.js`.

## Rebuild from source
Put the files in `src/` in one folder and run `python3 build.py` to write a new `index.html`.

## Known limits
- Not tested on a physical phone, and no sound yet.
- Visible water is a real droplet simulation, but income is set by the economy design; wheels spin from real water hits and pay-out popups show where the coins come from.
- Two stages (23, 26) let water pool for a while before it drains.
