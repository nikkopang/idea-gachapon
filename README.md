# Idea Gachapon

A capsule-toy machine for your ideas. Add ideas, turn the crank, and the machine drops a capsule with one of them inside. Tap the capsule to open it, then put the idea back or take it out of the machine.

## Run it

It's a single static file with no build step and no dependencies. Open `index.html` in a browser, or serve the folder:

```sh
python3 -m http.server 8000
```

Ideas are saved in your browser's `localStorage`, so they stay between visits on the same device.
