# 🌙 Moon Sling Shots

A 3D browser game: grab a moon, pull back the slingshot, and see how far you can fling it across an alien landscape.

**Pull distance = power. Pull angle = trajectory.** A deep pull aimed low fires a fast, flat screamer; a full pull at ~45° gets the big air. Thread the floating ⭐ stars mid-flight for escalating score bonuses — the more you chain in one flight, the more each is worth.

## Play

Deployed on Vercel, or run locally:

```bash
npx http-server . -p 4173
# open http://localhost:4173
```

No build step — a single `index.html` powered by [Three.js](https://threejs.org/) from CDN.

## Controls

| Input | Action |
|---|---|
| Click + drag the moon | Aim: pull back to charge, angle sets trajectory |
| Release | Launch 🚀 |
| `R` | Reset the current shot |

## Scoring

- Distance is measured where the moon comes to rest.
- Each ⭐ collected mid-flight adds a bonus (+25m, +30m, +35m… escalating per flight).
- Total = distance + star bonus. Best score and lifetime stars persist in `localStorage`.
- Ranks: Backyard Bounce → Crater Hopper → Orbit Curious → Escape Velocity → Lunar Legend → **Galactic Cannon**.
