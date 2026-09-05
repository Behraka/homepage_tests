# homepage_tests

Redesign concept for the Divorce Defenders homepage (divorcedefenders.com).

`index.html` is fully self-contained: images are embedded as data URIs, and the
only external requests are Google Fonts and GSAP from cdnjs.

## Public preview via GitHub Pages

1. Push `index.html` (and this README) to the `main` branch.
2. Repo **Settings → Pages**.
3. Source: **Deploy from a branch**. Branch: `main`, folder: `/ (root)`. Save.
4. Live in about a minute at `https://behraka.github.io/homepage_tests/`

The page carries `<meta name="robots" content="noindex, nofollow">` so the
preview cannot compete with divorcedefenders.com in search. Remove that line
only if you deliberately want it indexed.
