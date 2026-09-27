# Fresh Port

Brand and design system for **Fresh Port**, the premium imported-fruit store at HomePro Kanlapaphruek run by the family importer V.S.M. Fruit (est. 2002). *Straight from the port to our shelf.*

## Design system

Everything lives in [`design-system/`](design-system/):

| Folder | What's inside |
|---|---|
| [`BRAND-BOOK.md`](design-system/BRAND-BOOK.md) | The brand book: voice, logo rules, colour, type, layout, motion, Instagram post layout |
| [`tokens/tokens.json`](design-system/tokens/tokens.json) | Every colour, type style, spacing, radius, shadow and size, with a usage note on each |
| [`tokens/tokens.css`](design-system/tokens/tokens.css) | The same tokens as CSS variables, plus a class per type style. Themes: `light` (website), `dark` (navy), `cream` (business profile) |
| [`components/`](design-system/components/) | 18 components from the website, the business profile and Instagram. Open any `preview.html` in a browser; the styles are in `components/bundle.css` |
| [`assets/logos/`](design-system/assets/logos/) | Official logo vectors from the Illustrator PDFs: primary (white on midnight blue), navy and white |
| [`assets/graphic-elements/`](design-system/assets/graphic-elements/) | Instagram corner tabs, origin stamps, price blobs and the LINE pill |
| [`assets/icons/`](design-system/assets/icons/) | The website's 14 line icons |
| [`assets/photography/`](design-system/assets/photography/) | Store and product photos |

Start with [`design-system/index.html`](design-system/index.html) for a visual overview.

## Using the tokens

```html
<link rel="stylesheet" href="design-system/tokens/tokens.css">
<link rel="stylesheet" href="design-system/components/bundle.css">

<section data-theme="dark">   <!-- navy section -->
  <p class="fp-eyebrow">Why Fresh Port</p>
  <h2 class="fp-h2">Straight from the port to our shelf.</h2>
</section>
```

Colours: Midnight Blue `#112331` · White · Sea Mist `#EEF2F6` · Sail Cream `#F7F4EE` · Harbour Gold `#D4B26A`.
Fonts (Google Fonts): DM Serif Display, Prompt, and for Instagram DM Serif Text and Poppins.

## Sources

The design system was built from the live Shopify theme (freshportfruit.com), the business profile deck, the Brand Identity Guide, the official logo PDFs and the Instagram posts. Grower and partner logos are not included; they belong to those brands.
