# Teleprompter GitHub Page

A dependency-free teleprompter that works as a static GitHub Pages site.

AT: https://svetterio.github.io/VetterPrompter

## Controls

- `Space` — Play / pause scrolling
- `+` — Speed up scrolling; hold it for accelerating fast-forward
- `-` — Slow down scrolling; hold it for accelerating slowdown
- `Arrow Up` — Scroll backward from the current position
- `Arrow Down` — Scroll forward from the current position
- Hold the on-screen Back / Forward arrow buttons for continuous manual movement
- Manual arrow scrolling does not change the configured auto-scroll speed or play/pause state
- Speed steps adapt to the current speed: fine control at low speeds, larger jumps at high speeds
- `Ctrl + +` (or `Cmd + +`) — Enlarge text
- `Ctrl + -` (or `Cmd + -`) — Shrink text
- **Font dropdown** — Choose from teleprompter-friendly fonts: System Sans (recommended), Verdana, Arial/Helvetica, Trebuchet MS, Tahoma, Segoe UI, or Georgia
- On-screen buttons provide the same controls; hold the speed buttons for turbo adjustment
- `Edit Script` lets you paste your own script

The script, speed, font size, and selected font are stored locally in the browser using `localStorage`. Scrolling keeps fractional movement between frames so low speeds such as 10 px/s remain reliable.


## Version

Current release: **v1.0**

## Publish with GitHub Pages

1. Create a new GitHub repository.
2. Upload `index.html` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)` folder, then save.
6. GitHub will provide the public Pages URL after deployment.


## License

MIT License — Copyright (c) 2026 Sebastian Vetter <svetterIO@proton.me>. See `LICENSE` for the full license text.
