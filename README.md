# Warp Front

A browser-based solo card game where you coordinate three allied factions in a cooperative exact-sum race against the Borg. Using a standard deck of cards, the Federation (♦), Klingons (♥), and Ferengi (♣) must deploy warp speed to hit a planet's distance exactly. Meanwhile, the Borg (♠) act automatically, utilizing sudden bursts of speed to assimilate worlds by tying or overshooting the target. 

Built with AI coding assistance.

## Difficulty Levels

| Level | Rules |
|---|---|
| **Ensign** | Hand Size 4. Borg start with 0 planets assimilated. |
| **Standard** | Hand Size 3. Borg start with 0 planets assimilated. |
| **Admiral / Solo** | Hand Size 3. Borg start with a 1-planet head start. |

## Play

No build step or server is needed. Open the html file in any modern web browser.

## Publish with GitHub Pages

1. Push the file to a GitHub repository.
2. In the repository, go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, and save.

## Files

| File | Purpose |
|---|---|
| `index.html` | A fully self-contained application. Contains all page markup, UI styling, and the vanilla JavaScript game engine. |
| `WarpFrontRules.md` | The original rule set for physical cards. The origin of this project. |
