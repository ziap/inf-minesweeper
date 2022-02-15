# Infinite Minesweeper

![Coverage](https://img.shields.io/badge/coverage-97.75%25-green?style=for-the-badge)
![Total lines](https://img.shields.io/badge/TOTAL%20LINES-724-green?style=for-the-badge)
![Build size](https://img.shields.io/badge/BUILD%20SIZE-15.74KB-green?style=for-the-badge)

Minesweeper on an infinite board

![Preview](logo.png)

## Design goals

We want the game to be tiny, simple, and accessible.
So we decided to make it on the web, with no dependencies other than the standard web API.
That means we won't use:

-   Any game engine (like Phaser or Unity)
-   Any UI framework (like React or Vue)
-   Any Canvas library (like Pixi.js or P5.js)
-   Any preprocessor (like Sass or TypeScript)

Some other things we wanted to keep in mind:

-   :iphone: Mobile support is built-in. So the app must be:

    -   :triangular_ruler: Responsive.
    -   :rocket: Fast enough to run on a mobile device.
    -   :video_game: Touch-friendly. (support both touch and mouse input)

-   :sparkles: Decent, presentable graphics, animations, and UI.

-   :bar_chart: Clean, optimized, well-documented, heavily tested code.

## Instructions

### How to play

Go to [the website](https://infinite-minesweeper.vercel.app) or clone the project and run the HTML file.

### Controls

**Desktop**

-   Click and drag to move
-   Scroll the mouse wheel to zoom

**Mobile**

-   Tap and drag to move
-   Pinch to zoom

**Actions**

-   Left-click or tap to reveal a tile
-   Right-click to mark a cell as a mine
-   Toggle between reveal and mark with the flag button

Earn points by revealing tiles without a mine.

## Features

| :ballot_box_with_check: Done | :construction: In progress | :pushpin: Planned |
| ---------------------------- | -------------------------- | ----------------- |
| 2D infinite scrolling grid   | SFX                        | High scores       |
| Randomly placed mines        | Menu system                | Local leaderboard |
| Mobile support               | Multiple game modes        | PWA support       |
| Animations                   |                            |                   |

**:bulb: May or may not be implemented**

-   Online leaderboards/multiplayer
-   Seed based randomization
-   Improve performance with WebGL/WebWorkers/WebAssembly (Rust/C++)
-   Native desktop port with Rust and SDL2

## Made with

-   [HTML/CSS/JS](https://developer.mozilla.org/en-US/docs/Web/)
-   [Canvas](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/)
-   [Tailwind CSS colors](https://tailwindcss.com/docs/customizing-colors)
-   [Font Awesome](https://fontawesome.com/v6.0/icons/)
-   [ESLint](https://eslint.org/)
-   [Prettier](https://prettier.io/)
-   [Jest](https://jestjs.io/)
-   [Vite](https://vitejs.dev/)
-   [Vercel](https://vercel.com/)

# License

This app is licensed under the [AGPL-3.0 license](LICENSE).
