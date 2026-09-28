# Sky Rings - 3D Flight Simulator

A complete 3D flight simulator in a single HTML file, built with Three.js (loaded from a CDN).
No build step and no external assets - the terrain, textures, models and sound are all generated in code.

## Run locally
Open `index.html` in a modern browser (internet needed for the Three.js CDN), then press **Space**.

## Controls
| Key | Action |
| --- | --- |
| W / S | Pitch down / up |
| A / D | Roll left / right |
| Q / E | Yaw left / right |
| Shift / Ctrl (or R / F) | Throttle up / down |
| Space | Wheel brake |
| P / M / X | Pause / mute / reset to runway |

Takeoff: hold Shift for full throttle, then ease back on S at about 130 km/h. Fly through all 10 rings.

## Deploy
Static site - import the repo into Vercel with the default settings (no framework, no build command).
