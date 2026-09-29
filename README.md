# Dream Brainmatch — Shape Friends

A standalone, portrait-first memory game. Choose Practice or Beat Sparky, then a 4-, 6- or 8-card level. Matches earn another turn in Beat Sparky mode. Sparky's visible character art is held for a later pass; the opponent mode and voice remain playable.

Run `npm start` with Node 20+ and open <http://127.0.0.1:4178/>. No install or build step is needed. The root page opens `/shape-friends/`; that route also works when hosted under a GitHub Pages repository subpath.

Run `npm test` for logic, content, voice and animation checks. The browser playthrough is `node tests/shape-modes-browser.mjs` with a local server and Chrome debugging on port 9223. See [game documentation](shape-friends/README.md), [sprite-sheet brief](shape-friends/sparkysheet.md), [art provenance](shape-friends/ASSETS.md), and [QA limits](shape-friends/QA.md).

Pip's Garden and Barnyard Together are maintained separately in [Brainmatch-exp](https://github.com/Roky777/Brainmatch-exp).
