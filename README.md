# Wrong Audience: prototype (step 3)

Bovent Wu · CART 211 · Fall 2026

A 10-page website that pretends to be "Profilr", an ad company that builds a profile of me,
gets my interests exactly right, then recommends six things that miss every time.

## What's in this version

The 4 main pages, in HTML and CSS only (images are grey placeholders for now):

| Page | File |
|---|---|
| Home: my "audience profile" | `index.html` |
| Gallery of my interests | `interests.html` |
| Verdict 01 (template for verdicts 02 to 06) | `interest-01.html` |
| Error page: the profile breaks, I take over | `error.html` |

## Not done yet (next versions)

- Verdicts 02 to 06 and the receipt page
- Responsive layout (480px)
- JavaScript: loading screen, working cookie box, live tracker, rating pop-up that always lands on 1,
  locked Next button, animated accuracy bar
- The glitch getting stronger on every verdict

## Putting it online with GitHub Pages

1. Create a new repository on GitHub (for example `wrong-audience`).
2. Upload everything **inside** this folder (so `index.html` is at the top, next to `assets/`).
3. Go to Settings > Pages, choose "Deploy from a branch", branch `main`, folder `/ (root)`, and save.
4. After a minute, the site is at `https://YOUR-USERNAME.github.io/wrong-audience/`.
