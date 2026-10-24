# McCrack-Xbox

A browser-based Xbox Series X|S dashboard recreation project. The interface is designed around a full-screen console shell and controller-friendly navigation, using the official Xbox dashboard presentation as a visual reference.

## Current build

- Full-screen dashboard with atmospheric wallpaper, top quick-access icons, horizontal game tiles, quick access cards, and recent items
- Guide overlay with a console-style navigation rail and Profile, Friends, Notifications, Captures, Library, and Settings destinations
- Dedicated Home, My games & apps, Game Pass discovery, Store, Search, Settings, Profile, Friends, Notifications, Captures, and launch screens
- Keyboard and mouse interaction, keyboard focus movement, and browser Gamepad API input
- Custom game/app URLs, library tiles, recent list, local profile, accent color, and background themes saved to browser localStorage
- Game tile artwork loads from public game-library image URLs when available; gradient art is used as a fallback
- Static site; no build step or external JavaScript dependencies

## Run / publish

Open `index.html` in a modern browser, or enable GitHub Pages in **Settings → Pages**, selecting the `main` branch and `/(root)` folder.

Expected URL after Pages is enabled and published: https://patrickmango49.github.io/McCrack-Xbox/

## Controls

- Arrow keys or WASD: move focus
- Enter: select
- Escape: back / close overlay
- G: toggle the Guide
- Xbox controller: D-pad or left stick to move, A to select, B to go back, Menu to toggle the Guide (browser Gamepad API support varies)

## Honest limitations

This is a fan-made browser recreation, not an actual Xbox OS and not affiliated with Microsoft. It does not connect to Xbox Network, Xbox account sign-in, official achievements, parties, messages, cloud saves, Quick Resume, subscriptions, purchases, or native console game launching. Web games can only be embedded when their websites allow iframe embedding; otherwise use the open-in-new-tab action. Do not enter Microsoft account credentials into this recreation.

The goal is to keep improving the visual fidelity and interaction details against publicly available Xbox dashboard references while keeping the implementation an independent browser project.
