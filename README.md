# RockWeave (Marley's Match-3 Game)

[![CI](https://github.com/denisecase/rockweave/actions/workflows/ci.yml/badge.svg)](https://github.com/denisecase/rockweave/actions/workflows/ci.yml)
[![Deploy](https://github.com/denisecase/rockweave/actions/workflows/deploy.yml/badge.svg)](https://github.com/denisecase/rockweave/actions/workflows/deploy.yml)
[![CodeQL](https://github.com/denisecase/rockweave/actions/workflows/codeql.yml/badge.svg)](https://github.com/denisecase/rockweave/actions/workflows/codeql.yml)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
![Node](https://img.shields.io/badge/node-22.x-339933?logo=node.js)
![typescript dev dep](https://img.shields.io/github/package-json/dependency-version/denisecase/rockweave/dev/typescript)
![vite dev dep](https://img.shields.io/github/package-json/dependency-version/denisecase/rockweave/dev/vite)
![Code Style: Prettier](https://img.shields.io/badge/code_style-Prettier-ff69b4?logo=prettier)
[![GitHub Pages](https://img.shields.io/badge/site-live-brightgreen)](https://denisecase.github.io/rockweave/)

[Lighthouse Scores (out of 100)](https://denisecase.github.io/rockweave/lighthouse.html)

[![Lighthouse Accessibility Badge](./assets/img/scores/lighthouse_accessibility.svg)](https://github.com/denisecase/rockweave)
[![Lighthouse Best Practices Badge](./assets/img/scores/lighthouse_best-practices.svg)](https://github.com/denisecase/rockweave)
[![Lighthouse Performance Badge](./assets/img/scores/lighthouse_performance.svg)](https://github.com/denisecase/rockweave)
[![Lighthouse SEO Badge](./assets/img/scores/lighthouse_seo.svg)](https://github.com/denisecase/rockweave)

A match-3 puzzle game built with TypeScript and HTML5 Canvas.
Installable as a Progressive Web App (PWA).

---

Features:

- 8x8 board with 6 to 7 rock kinds
- Swap adjacent cells by tapping them if the swap will form a match of 3 or more in a row
- Find matches, clear, collapse, refill
- Basic scoring and moves

## Controls

- Click a cell and then click an adjacent cell to try a swap.
- Valid swaps that create matches (3 in a row, same color) will clear and cascade.

## How the Game Logic is Organized

The main code is in the [`src`](./src/) folder. For an overview, see: [`SRC.md`](./SRC.md)

## Making Changes

To make changes, see: [`CUSTOMIZING.md`](./CUSTOMIZING.md).
