# PetStock Landing Page

Landing page of **PetStock**, the inventory and sales platform for small pet stores, built by **Nexora** for the Web Applications course (1ASI0730) at UPC.

| | URL |
|---|---|
| Landing page | https://1asi0730-2620-8074-petstock.github.io/LandingPage/ |
| Web application | https://petstock-frontend.onrender.com |

## Tech stack

HTML5, CSS3 and JavaScript, with no frameworks or build step.

## Structure

| Path | Content |
|---|---|
| `index.html` | Sections: hero, benefits, how it works, pricing, previews, FAQ and footer |
| `styles/` | One CSS file per section, plus `general.css` |
| `assets/` | Images of the application |
| `assets/i18n/` | Texts in Spanish (`es.json`) and English (`en.json`) and the language switcher (`i18n.js`) |

The **Iniciar sesión** button opens the web application.

## Run locally

Serve the folder with any static server, for example:

```bash
npx serve .
```

A static server is needed because the translations are loaded with `fetch`.

## Deployment

GitHub Pages publishes the `main` branch.

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) and [CHANGELOG.md](CHANGELOG.md).

## License

[MIT](LICENSE)
