# CNA Shift

A small 3D browser game about working a day shift as a certified nursing assistant (CNA). It's a demo, built to play on a phone.

Answer call lights on Hall B from 7 AM to 3 PM (two real minutes):

- **Drag anywhere** to walk (or use WASD / arrow keys on a computer).
- Walk into the **Water, Meals, or Linens** cart to pick up what a resident asked for, then bring it to their bed.
- **Turning** 🔄 and **vitals** 🩺 need no supplies: stay at the bedside until the bar fills.
- Step on the **sanitizer** ring between residents for a clean-hands bonus.
- Faster help scores more. A call light that runs out costs points.

## Run it

It's a single file, `index.html`, with no build step. Open it in any modern browser, or serve the folder:

```sh
npx serve .
```

Three.js loads from the jsDelivr CDN, so the first load needs an internet connection.
