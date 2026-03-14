# 🎯 Guess Game — Numbers and Wizards

A number guessing game built with **Unity** and **C#**, where the computer tries to guess the number *you're* thinking of using the **binary search** algorithm. The game narrows down possibilities with each guess, finding your number in the fewest tries possible.

## 🕹️ Play Now

👉 **[Play in your browser](https://stabgan.github.io/guessgame/)** — no install needed!

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| 🎮 **Unity 2018.3** | Game engine |
| 💻 **C#** | Game logic & scripting |
| 🌐 **WebGL** | Browser-based deployment |
| 🍎 **macOS Build** | Native desktop app (.app bundle) |
| 🧮 **Binary Search** | Core guessing algorithm |

## 🎲 How to Play

1. Think of a number within the given range
2. The game will make a guess using binary search
3. Tell the game if your number is **higher**, **lower**, or **correct**
4. The game refines its guess each round, halving the search space
5. See how few attempts it takes to find your number!

### Platforms

- **Web** — Play directly at [stabgan.github.io/guessgame](https://stabgan.github.io/guessgame/)
- **macOS** — Download and run the `.app` bundle from the `Guess Game MacOS .app/` directory

## ⚠️ Known Issues

- The WebGL build uses **Unity 2018.3** and may have compatibility issues with newer browsers
- The macOS build targets **macOS 10.9+** and may require allowing unsigned apps in Gatekeeper
- WebGL build requires **WebGL 2.0** (falls back to WebGL 1.0) — some older devices may not support this
- The macOS `.app` bundle is unsigned (`com.Company.ProductName` identifier), so macOS may block it on first launch
- No Windows or Linux native builds are currently provided

## 📄 License

[MIT License](LICENSE) © 2019 Kaustabh Ganguly

---

*Image assets: [People vector created by Brgfx — Freepik.com](https://www.freepik.com/free-photos-vectors/people)*
