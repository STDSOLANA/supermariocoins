# 🌙 MOONRUN — Arcade Coin Dash

A fast, original, browser-based arcade game. **Collect coins, dodge hunter drones, dash through danger, and set a high score in 60 seconds.**

**▶ [Play the game](https://stdsolana.github.io/supermariocoins/)** (requires GitHub Pages to be enabled — see below)

## Features

- Fast arcade survival gameplay with movement, enemies and dash attacks
- Coin combos and saved local high scores
- Keyboard and on-screen touch controls
- Built entirely with HTML, CSS and vanilla JavaScript
- No npm, trackers, accounts, backend, crypto wallets, or external assets
- MIT-licensed original code so anyone can fork, change and host it

## Controls

| Action | Keyboard |
| --- | --- |
| Move | Arrow keys or WASD |
| Dash | Space |
| Pause / resume | P |
| Restart | R |
| Start | Enter or Start Run button |

Touch controls appear on mobile devices.

## Play locally

**Simplest:** Download this repository using **Code → Download ZIP**, extract it and open `index.html` in a modern browser.

Alternatively, serve it locally:

```sh
python -m http.server 8000 --bind 127.0.0.1
```

Then open http://127.0.0.1:8000/.

No build step or package installation is needed.

## Publish your fork

1. Fork this repo using GitHub's **Fork** button.
2. Open your fork → **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Choose `main` and `/(root)`, then save.
5. GitHub should provide a URL like `https://YOUR-USERNAME.github.io/supermariocoins/`.

You may rename, customize, or deploy the game on your own site subject to the [MIT License](LICENSE).

## Screenshots

To add real screenshots, create a `screenshots/` directory, play the game and capture a title screen and gameplay with your browser screenshot tool. Embed them in this README using:

```md
![MOONRUN gameplay](screenshots/gameplay.png)
```

Please do not substitute screenshots of another game.

## Contributing

Bug fixes, accessibility improvements, new original levels and mechanics, performance improvements, translations and documentation are welcome. Read [CONTRIBUTING.md](CONTRIBUTING.md).

## Credits and licensing

**MOONRUN is an original independent project, not Super Mario 64.** This repository does **not** include Mario, Nintendo imagery, third-party Mario ports, or their game files. Nintendo and Super Mario are trademarks of their respective owners; this project is not affiliated with or endorsed by Nintendo.

The original MOONRUN source code in this repository is licensed under [MIT](LICENSE). Please keep copyright notices and respect licenses for any future outside contributions/assets.
