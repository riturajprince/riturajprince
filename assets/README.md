# Profile artwork

The profile follows [Ritu Raj Prince’s About page](https://www.riturajprince.in/about), captured on November 10, 2026. College and postgraduate details are intentionally omitted from the profile text and artwork.

- `header.svg` and `footer.svg` use the website’s portrait, DM Sans typography, charcoal background (`#0b0c0e`), cream text (`#f6f3f0`), and blue accent (`#0055fe`). Their liquid-glass animations respect `prefers-reduced-motion` and have a complete static appearance. They contain no scripts or external resources.
- The `about`, `stack`, `expertise`, `work`, `projects`, `principles`, `faq`, and `connect` sections each have `-desktop.png` and `-mobile.png` artwork rendered at twice the display resolution. The README selects the appropriate layout with `<picture>`. Sections follow the website’s HTML, CSS, DM Sans, and Cormorant Garamond typography; carousels become complete grids and the FAQ displays its answers.
- `nav-*.svg` and `link-*.svg` provide glass buttons with real README links. Actions are kept outside the section artwork so they remain clickable.
- `icons/` contains all 13 technologies from the earlier profile, plus Node.js and Tailwind CSS from the website. Logos come from [Devicon v2.17.0](https://github.com/devicons/devicon/tree/v2.17.0), under its [MIT license](icons/LICENSE.txt). The AWS wordmark uses cream lettering for contrast on the dark background.
- The expandable **Profile details** section provides the same content as accessible, searchable text.

The embedded DM Sans font is distributed under the [SIL Open Font License](DM-Sans-LICENSE.txt). Older assets are retained but are not referenced by the current profile unless listed above.

GitHub controls the README’s outer layout. The section artwork preserves the website’s typography and glass panels, while navigation and project/contact links use GitHub-supported HTML.
