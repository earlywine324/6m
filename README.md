# Goodtime State Roleplay community website

Navy-and-gold GTA VI community website concept with an interactive roadmap.

## Pages
- `index.html`: community homepage with eight numbered image placeholders.
- `roadmap.html`: progress, milestones, updates, and a browser-local demo editor.
- `Goodtime State Roleplay-Mockup.html`: self-contained homepage export; roadmap links require the other files alongside it.

## Preview
Run `python3 -m http.server 4173` in this directory, then open http://localhost:4173.

## Hosting
Static HTML, CSS, and JavaScript. No dependencies or build step. Import this repository into Vercel using the Other framework preset and repository root as the root directory. The included vercel.json sets the static output directory.

## Demo limitations
Admin access is simulated and available to anyone. Changes are stored only in the current browser's localStorage, not shared between visitors. Hidden roadmap items are not private. Do not enter sensitive information. Real authentication, server-side authorization, shared storage, and account management must be implemented before this can function as a production administration system.

Progress, dates, departments, and recruitment content are illustrative. In-game plans depend on supported GTA VI multiplayer capabilities. Goodtime State Roleplay is independent and is not affiliated with Rockstar Games, FiveM, or FDLE.

## Image placeholders
01 hero; 02 Leonida map/aerial; 03 community roleplay; 04 law enforcement; 05 fire & rescue; 06 civilian life; 07 communications; 08 closing banner.
