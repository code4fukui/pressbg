# pressbg

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

A project by **Code for Japan** x **Code for FUKUI**.

A dynamic background generator that creates a real-time, adjustable tiling grid of logos. Perfect for use as a backdrop during online presentations, conferences, and events.

## Demo

**Live demo:** [**https://github.com/code4fukui/pressbg](https://code4fukui.github.io/pressbg/)

## Features

*   **Alternating Logo Grid:** Displays a full-screen, checkerboard-style pattern of the Code for Japan and Code for FUKUI logos.
*   **Real-time Density Control:** Instantly adjust the number of tiles in the grid using keyboard controls.
*   **Fullscreen Mode:** Click anywhere to toggle a fully immersive view.
*   **Zero-dependency:** Runs directly in the browser from a single HTML file with no build step.

## Controls

*   **`↑` Arrow Key**: Increase grid density (up to 50x50).
*   **`↓` Arrow Key**: Decrease grid density (down to 2x2).
*   **Mouse Click**: Toggle fullscreen mode.

## Usage

To run locally, clone the repository and open `index.html` in any modern web browser.

```bash
git clone https://github.com/code4fukui/pressbg.git
cd pressbg
# Open index.html in your browser
```

## Implementation

This project is a single `index.html` file that uses vanilla JavaScript (ES Modules) and the browser's Fullscreen API. It relies on [stdom.js](https://js.sabae.cc/stdom.js) for lightweight DOM manipulation, which is loaded from the `js.sabae.cc` CDN.

## License

See [LICENSE](LICENSE).