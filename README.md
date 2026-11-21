# Small Projects

A collection of small browser projects. Each lives in its own folder as a standalone page with no build step.

Live: https://vadymzelenko.github.io/lite-pet-projects/

| Project | Description | Stack |
|---|---|---|
| [`RSVP-reader`](RSVP-reader) | Speed reader that shows text one word at a time (rapid serial visual presentation). Opens TXT and FB2 files, adjustable words per minute, reading progress saved in `localStorage`. | JavaScript |
| [`photo-sudoku-solver`](photo-sudoku-solver) | Upload a photo of a sudoku: the grid is recognised with OCR, can be corrected by hand and is then solved. | JavaScript, Canvas, OCR |
| [`Atom-3D`](Atom-3D) | 3D model of the atom of any chemical element: protons, neutrons and electron shells from `elements.json`, element search with autocomplete. | Three.js |
| [`Portfolio-with-game-Life`](Portfolio-with-game-Life) | Personal business-card page with Conway's Game of Life as an animated background and a QR code. | HTML, CSS, JavaScript |

## Running locally

Pages that load data with `fetch` (Atom 3D) need to be served over HTTP:

```bash
npx serve .
# or
python3 -m http.server 8000
```

## License

[MIT](LICENSE) © Vadym Zelenko
