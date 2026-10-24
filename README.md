# McCrack-Xbox

An unofficial browser-based recreation inspired by the Xbox Series X|S dashboard. It is designed as an interactive console-style shell rather than a static mockup.

## Current features

- Dashboard with recently launched shortcuts and pinned tiles
- Guide overlay with Home, Profile & system, Friends & community, Notifications, Captures, Library, and Settings destinations
- Game/app library with custom URL shortcuts, launch screen, optional iframe attempt, and open-in-new-tab fallback
- Discover page and console-style Settings categories
- Local profile name, accent color, pins, recent items, and custom shortcuts saved with browser localStorage
- Keyboard navigation (arrow keys / WASD, Enter, Escape, G for Guide)
- Xbox controller support via the browser Gamepad API (D-pad/stick, A, B, Menu where the browser exposes them)
- Responsive layout and no build step or external dependencies

## Run locally

Open `index.html` in a modern browser, or serve this folder using any static web server.

## Deploy with GitHub Pages

1. Open repository **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select `main` and `/(root)`, then save.
4. Wait for the deployment to finish.

Expected URL: https://patrickmango49.github.io/McCrack-Xbox/

## Important limitations

This is an independent fan-made browser recreation, not an actual Xbox operating system and not affiliated with or endorsed by Microsoft. A true 1:1 copy of the full console software is not possible from a static website: Xbox Network sign-in, friends, parties, messages, cloud saves, official achievements, Quick Resume, Store entitlements, system-level settings, and native game launching require Microsoft's services or console-level access and are not implemented here. Game sites may block iframe embedding; use the new-tab option when that happens.

The project can continue to get closer visually and behaviorally through original frontend code and publicly available references, but it should not collect Xbox passwords or impersonate Microsoft's sign-in flow.
