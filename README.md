# Midnight Arcade

Five original browser-game prototypes: Blood Moon City, The Last Sunset, Hunger Engine, Nocturne, and The Midnight Court. The collection runs entirely in the browser with no build step, accounts, backend, or payment integration.

## Run locally

Serve the project root using a static web server, for example `python3 -m http.server 8000 --directory dist`, then open http://localhost:8000.

## Deploy to Vercel

Import this repository in Vercel. The included `vercel.json` sets `dist` as the output directory. Choose **Other** as the framework preset; no build command or environment variables are needed. Deploy the branch and use the generated URL.

Keyboard and pointer controls are shown in each game. Sound is opt-in. Best scores are saved in localStorage on the player's device. These are prototypes, not payment-enabled commercial releases.

## Current game mechanics

- **Blood Moon City:** feed to restore health and earn upgrade choices; pulse defeats nearby hunters and destroys streetlights.
- **The Last Sunset:** collect three moonstones while moving shadows offer protection from sunlight and rotating searchlights.
- **Hunger Engine:** move or stand your ground to evolve; choose upgrades and defeat the hunter arriving late in the run.
- **Nocturne:** collected notes form a looping melody, with additional layers unlocked during play. Sound is opt-in.
- **The Midnight Court:** seven distinct story encounters with resource consequences and multiple endings.

These remain early game builds. Automated checks cover starts, the evolution selection, boss spawning, note storage, and a court turn; they are not a substitute for complete human playtesting or real-device performance testing.
