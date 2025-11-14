# Apple App Store frontend source code archive

Extracted from [https://apps.apple.com/](https://apps.apple.com/). Saved using the Chrome extension [Save All Resources](https://chromewebstore.google.com/detail/save-all-resources/abpdnfjocnmdomablahdcfnoggeeiedb). This is a fork to hopefully preserve this a while longer.

### How is this possible?

Apple forgot to disable sourcemaps in production on the App Store website. They since removed them, but these archives are still available.

<img width="795" height="548" alt="image" src="https://github.com/user-attachments/assets/59211dfb-5a56-456b-85b8-d292c1cfbfa2" />

As an interesting discovery, I've archived them here on GitHub for educational purposes.

## Directory Structure

```
.
├── api/          # API related code
├── assets/       # Static assets
├── node_modules/ # Dependencies
├── shared/       # Shared modules
├── src/          # Source code
│   ├── components/
│   ├── config/
│   ├── constants/
│   ├── context/
│   ├── stores/
│   └── utils/
└── us/           # US region specific
```

## What's Inside

- Complete Svelte/TypeScript source code
- State management logic
- UI components
- API integration code
- Routing configuration
- And more...

## Disclaimer

This repository is for educational and research purposes only. All code is copyrighted by Apple Inc.

The source code was obtained from publicly accessible resources through browser developer tools.

## License

The content in this repository belongs to Apple Inc. But they made it public... so as far as I know its legal to study these (but dont use them in your own stuff!)

---

*Remember: Always disable sourcemaps in production!*

## Related

- [Apple App Store](https://apps.apple.com/)
- [Save All Resources Extension](https://chromewebstore.google.com/detail/save-all-resources/abpdnfjocnmdomablahdcfnoggeeiedb)
