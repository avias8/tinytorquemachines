# Tiny Torque Machines website

The public site for Tiny Torque Machines: the game page, support and the
privacy policy, served by GitHub Pages at
https://www.avivarma.ca/tinytorquemachines/.

Plain HTML and CSS with no third-party requests. `index.html` is generated
from the game's own data (circuits, cars, weapons) by
`tools/website/build.mjs` in the game's repository; edit that script, not the
page. `support.html`, `privacy.html` and `style.css` are written by hand.
Push to `main` and Pages republishes in a minute or two.

The game's repository includes this one as a submodule at `website/`.
