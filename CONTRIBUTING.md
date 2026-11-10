# Contributing

## Branches

We use a simple GitFlow:

| Branch | Purpose |
|---|---|
| `main` | Published version (GitHub Pages). It is updated from `release/x.y.z` branches. |
| `develop` | Integration branch. |
| `feature/<name>`, `fix/<name>`, `docs/<name>` | Created from an updated `develop` and merged back with a pull request to `develop`. |
| `release/x.y.z` | Created from `develop`, merged into `main`, tagged `vx.y.z` and merged back into `develop`. |

Never open a pull request from a feature branch to `main`.

## Commits

Follow [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) in English, with the `landing` scope:

```
feat(landing): add pricing section
```

## Code style

- Keep the styles of each section in its own file in `styles/`.
- Every visible text needs a `data-i18n` key with its value in `assets/i18n/es.json` and `assets/i18n/en.json`.
- Check the page on mobile and desktop widths before opening a pull request.
