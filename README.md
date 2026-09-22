# Playground

<img src="https://raw.githubusercontent.com/shadrackb1/shadrackb1/main/mini-games.svg" width="100%" alt="mini games preview" />

Mini games and interaction experiments. No frameworks, no build step. Each HTML file is the whole app, so you can open one in a browser tab and play.

**Hard constraint it answers:** demos you can show in five seconds on any machine. Nothing to install, nothing to compile, works from a USB stick or GitHub Pages.

**Live:** https://shadrackb1.github.io/playground/

## Games and labs

| Piece | What it is | Controls | File |
| --- | --- | --- | --- |
| Snake | Classic grid snake. Speed rises with score. | Arrows / WASD / swipe · Space pauses | [snake.html](./snake.html) |
| Pong | Single-player against a simple AI. First to 7. | Mouse / touch | [pong.html](./pong.html) |
| 2048 | Classic merge puzzle. Local best score. | Arrows / swipe | [game-2048.html](./game-2048.html) |
| Mines | 10×10 board, 15 mines. | Click · right-click to flag | [mines.html](./mines.html) |
| Memory | Match the pairs. Tracks moves and time. | Click | [memory.html](./memory.html) |
| Reaction | Wait for green, then click. Measures ms. | Click | [reaction.html](./reaction.html) |
| USSD simulator | Dial `*384#` and walk an attendance session like a feature phone. | Click through menus | [ussd.html](./ussd.html) |
| RIS lab | Browser mock of the USB RAG loop: ingest, retrieve, cite. | Click through the loop | [ris-lab.html](./ris-lab.html) |
| Credentials hub | 24 AI certs with platform verification links. | Browse | [credentials.html](./credentials.html) |

The USSD and RIS labs are demos of live products: [ussd-attendance](https://github.com/shadrackb1/ussd-attendance) and [research-in-a-stick](https://github.com/shadrackb1/research-in-a-stick).

## Stack

Static HTML + CSS + vanilla JS. Canvas where a game needs it. No dependencies, no CDN required for the games themselves.

## Run locally

Open any HTML file in a browser, or clone and use the live Pages build:

```bash
git clone https://github.com/shadrackb1/playground.git
start index.html    # Windows
open index.html     # macOS
xdg-open index.html # Linux
```

GitHub Pages is already on: https://shadrackb1.github.io/playground/

## Links

- Live: https://shadrackb1.github.io/playground/
- Profile: https://github.com/shadrackb1
- Related: [shadrack-portfolio](https://shadrack-portfolio-alpha.vercel.app)

## License

MIT
