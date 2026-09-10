# Vanilla JavaScript Games

Two browser games built with **plain JavaScript, HTML, and CSS**: Minesweeper and Tic-Tac-Toe. There is no framework, dependency installation, or build pipeline.

## Play locally

From the repository root, start a static server. For example, with Python 3:

```sh
python -m http.server 8000 --bind 127.0.0.1
```

| Game | Local URL | Source |
| --- | --- | --- |
| Minesweeper | `http://127.0.0.1:8000/buscaminas/` | [buscaminas/](buscaminas/) |
| Tic-Tac-Toe | `http://127.0.0.1:8000/tic-tac-toe/` | [tic-tac-toe/](tic-tac-toe/) |

Each game keeps its HTML, JavaScript, and styles in its own directory. The Minesweeper directory retains its original Spanish name, `buscaminas`.

## Screenshots

### Tic-Tac-Toe

![Tic-Tac-Toe board](https://pbs.twimg.com/media/EfgYdjvXYAE0KJJ?format=jpg&name=large)

### Minesweeper

![Minesweeper board](https://pbs.twimg.com/media/EhXfaOTXsAATdcg?format=png&name=small)

## Validation

There is no automated test suite. When changing a game, check normal moves, win/loss conditions, and any reset controls in the browser. Inspect the console for errors and confirm that styles and scripts load. The screenshots above are the original externally hosted images; their availability has not been verified.
