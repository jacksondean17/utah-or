# Utah or Morocco?

A tiny photo quiz: 20 red-rock geology images, and you have to guess whether each
one was shot in southern Utah or in Morocco. No sand dunes, famous arches, beaches,
or obvious landmark giveaways — just rock that looks suspiciously similar across two
continents.

**Play it:** https://jacksondean.space/utah-or/

## How it works

- A single self-contained `index.html` — HTML, CSS, and a little vanilla JavaScript.
  No build step, no dependencies.
- Photos are hot-linked from [Wikimedia Commons](https://commons.wikimedia.org/);
  a source-and-license link appears after every guess.
- Keyboard controls: **U** / **M** to answer, **→** or **Space** for the next image,
  **R** to shuffle and restart.

## Run locally

Just open the file:

```sh
git clone https://github.com/jacksondean17/utah-or.git
cd utah-or
# open index.html in a browser, or:
python -m http.server 8000   # then visit http://localhost:8000
```

## Deployment

Hosted on GitHub Pages from the `main` branch root. Pushing to `main` redeploys.

## Image credits & license

All quiz photos belong to their respective authors on Wikimedia Commons and are used
under their individual licenses (linked in-app after each guess). The quiz code itself
is released under the MIT License.
