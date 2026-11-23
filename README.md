# Never Twice

A page that looks different on every load. A random copypasta and random replies are picked with a little JavaScript, and the styling (hue, type size and weight, letter tilts, card tilts, corner radius, gaps) comes from the CSS `random()` function.

Browsers that don't support `random()` yet get a small JavaScript stand-in that rolls the same ranges. The chip in the top bar shows which mode you're in.

Based on [Understanding CSS random()](https://piccalil.li/blog/understanding-css-random) on Piccalilli.

Deployed to GitHub Pages by `.github/workflows/pages.yml` on every push to `main`.
