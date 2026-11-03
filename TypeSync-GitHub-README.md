# TypeSync

> Maintained by [@theAmbi](https://github.com/theAmbi)

**Figma-style text styles for Photoshop.** Create, organise and update typography across every text layer in your document — from one compact panel.

TypeSync is a native Photoshop UXP plugin. Define a text style once, link it to the text layers you choose, and update every linked layer at once when the style changes.

## Features

- **Text styles, not guesswork** — capture font family, style, size, leading, tracking, capitalization and justification from a selected text layer, then apply them to any other layer.
- **Linked layers** — styles are explicitly linked to the layers you select. Editing a style updates every linked layer in the active document; renaming a style never breaks its links.
- **Folders and nesting** — organise styles with slash-separated names (`Headings/H1`, `Paragraphs/P1/Normal`), collapsible nested folders, manual folder creation and drag-and-drop reordering.
- **Find linked layers fast** — click a style's linked count to select its layers and flash their labels yellow so you can spot them instantly.
- **Points, not pixels** — sizes and leading are stored in points and converted correctly for each document's resolution.
- **Eight languages** — English, Spanish, French, German, Brazilian Portuguese, Japanese, Korean and Simplified Chinese, with automatic detection from Photoshop's interface language.
- **Dark and light** — the panel follows your Photoshop theme.
- **Private by design** — everything is stored locally in the plugin. No accounts, no network access, no tracking.

## Requirements

- Photoshop 24.1 or newer (UXP)

## Known limitation

Do not scale or stretch a text box manually with Free Transform — Photoshop records that as a layer transform, so reported font sizes no longer match what you see. Resize text by editing the style or font size instead. If a layer was already transformed, reset its scale to 100% before linking it.

## Privacy and terms

TypeSync stores your styles and layer links locally on your machine. It collects no data and makes no network requests.

- [Privacy policy](https://theambi.github.io/typesync-docs/privacy-policy)
- [Terms of service](https://theambi.github.io/typesync-docs/terms-of-service)

## Support

Questions or issues: photoshopwithgolden@gmail.com, or open an issue on [GitHub](https://github.com/theAmbi).

## License

All rights reserved. TypeSync is distributed through the Adobe Creative Cloud Marketplace; see the terms of service for usage rights.
