# ezequielboussard.github.io

This repository exists so that `https://ezequielboussard.github.io` does not return a 404. It serves a single `index.html` that redirects to [ezequiel.is-a.dev](https://ezequiel.is-a.dev), which is the actual portfolio.

GitHub Pages cannot answer with a 301, so the redirect is client-side and comes in three layers: `meta refresh`, `location.replace`, and a visible link in case JavaScript is blocked. The `canonical` points at the destination so search engines do not index this intermediate page.

`.nojekyll` keeps GitHub Pages from running the site through Jekyll, which it has no use for.

Nothing else lives here. Projects have their own repositories.
