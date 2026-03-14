# Guess Game

A number-guessing game built with Unity and C#. Think of a number, and the game tries to guess it in as few attempts as possible using a binary search strategy.

## ▶️ Play

**[Play in your browser](https://stabgan.github.io/guessgame/)**

A macOS standalone build is also included in the repo (`Guess Game MacOS .app`).

## How It Works

The game asks you to think of a number within a range, then narrows down the possibilities by asking higher/lower questions — classic binary search in a friendly UI.

## 🛠 Tech Stack

| | Technology | Purpose |
|---|---|---|
| 🎮 | Unity (WebGL) | Game engine & browser build |
| 💻 | C# | Game logic |
| 🌐 | HTML / CSS / JS | WebGL host page & loading UI |

## Run Locally

1. Clone the repo
2. Open `index.html` in a browser (or serve via any static file server)

> A local HTTP server is recommended since some browsers block WebGL from `file://` URLs:
> ```
> python -m http.server 8000
> ```
> Then visit `http://localhost:8000`

## Project Structure

```
├── index.html              # Entry point (loads Unity WebGL player)
├── Build/                  # Unity WebGL build artifacts
├── TemplateData/           # Loading screen assets & styles
└── Guess Game MacOS .app/  # Standalone macOS build
```

## ⚠️ Known Issues

- The Unity WebGL build targets an older Unity version; some modern browsers may show deprecation warnings for the WebAssembly loading method.
- The macOS `.app` bundle is unsigned and may require Gatekeeper override to run.

## Credits

- Game by [Kaustabh Ganguly](https://github.com/stabgan)
- Character art: [Brgfx via Freepik](https://www.freepik.com/free-photos-vectors/people)

## License

See [LICENSE](LICENSE) for details.
