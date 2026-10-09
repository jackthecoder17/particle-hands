# Particle Hands

Control thousands of particles of light with your bare hands — right in the browser.
Real-time hand tracking (MediaPipe) + a custom particle engine (Three.js + bloom). No install.

## Gestures

| Gesture | Effect |
| --- | --- |
| ✊ Fist | Black hole — swallows everything into an accretion disk |
| ✊ → ✋ Release | Supernova shockwave |
| 🤏 Pinch | Spiral galaxy |
| 🤏 + 🤏 Both pinch | DNA-helix energy beam between your hands |
| ☝️ Point | Paint with light |
| ✋ Open palm | Force field |

Hands out of frame → the particles reform your text.

## URL options

- `?text=YOUR|NAME` — text the particles form (`|` = new line)
- `&theme=cosmic|ember|aurora|gold|naija`
- `&by=@handle` — on-screen credit

## Keys

`R` record (exports MP4/WebM) · `T` text · `C` theme · `V` camera brightness · `S` skeleton · `H` hide UI

## Run locally

```bash
python3 -m http.server 5173
```

Then open http://localhost:5173 (camera requires localhost or HTTPS).
