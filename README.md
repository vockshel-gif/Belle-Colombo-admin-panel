# Belle Colombo — Executive Studio & Admin Cockpit

Executive content management suite and live simulator for Belle Colombo restaurant application.

## Structure
- **`index.html`**: The Executive Studio & Content Cockpit (entrypoint hosted via GitHub Pages)
- **`preview.html`**: Belle Colombo Client Application (embedded inside the live interactive device simulator)
- **`belleData.js`**: Default master menu data, venue settings, and tasting odysseys
- **`assets/`**: High-resolution dish photos, cinematic vertical video backdrops, and event assets
- **`Logo/`**: Belle Colombo brand assets and typography vectors

## Hosting & Live Preview
- **Live Studio Entry**: `index.html`
- **Realtime Sync**: Communicates in real-time with the simulated client application via `postMessage`, `BroadcastChannel`, and Google Firebase Realtime Database.
