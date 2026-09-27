Fresh Port is a premium fruit store run by a family importer (V.S.M. Fruit, est. 2002). The core idea is **Straight from the port to our shelf.** (ส่งตรงจากท่าเรือ สู่ชั้นวางของเรา). Every surface should feel clean, calm and well lit: Midnight Blue as the constant, fruit as bright cargo, honest pine crates and flashes of harbour gold.

The brand shows up in three places. Each has its own theme and components, all built from the same tokens:

| Surface | Where | Grounds | Accent | Theme |
|---|---|---|---|---|
| **Website** | freshportfruit.com, for shoppers | white, sea-mist bands, navy hero/partners/footer | none; navy does the work | `light` + `dark` sections |
| **Business profile** | the /pages/business-profile deck, for landlords and retail partners | alternating navy and cream slides | harbour gold | `dark` + `cream` |
| **Instagram** | product posts | studio photo, navy cloth | fruit colours, corner tab | see its section |

## Content fundamentals

- **Voice:** warm, knowledgeable, honest, quietly proud. Think of a well-travelled fruit merchant with local roots.
- **Bilingual:**
  - **Website:** English headline with a Thai line under it.
  - **Business profile, B2B and in-store material:** Thai first, with English in italic under it.
  - Always set Thai in Prompt.
- **Business profile voice:** quietly proud and data-led. Lead with "Most fruit stores buy from the market. We supply the market." (ร้านผลไม้ส่วนใหญ่ซื้อจากตลาด — แต่เราคือผู้ส่งผลไม้เข้าตลาด), then give the proof: 20+ years, 80%+ direct import, 8+ origins, and the stores already open. The pitch is a long-term partner, not a seasonal tenant.
- **Be specific:** name the variety and the origin ("Arihyang strawberries from Korea", "Santina cherries from Chile — early-season, firm and sweet").
- **Every price shows its unit:** `300.-` in `price`, then `/500 g` in `caption`.
- **Frame big claims as aims.** Never say "best", "cheapest", "ดีที่สุด", "ถูกที่สุด" or "100% guaranteed". No ALL-CAPS shouting and no strings of exclamation marks. Social posts get 1–2 emoji at most (fruit and flag), and none on the website or signage.
- **Keep off the website:** refund policy, the store phone number and LINE Shopping links. The only calls to action are "visit the store" and "chat on LINE @freshport".
- **Taglines:** "Freshly imported for you." · "Quality you can see. Freshness you can feel." · "Picked with care. Delivered with trust."
- **Word bank:** direct import, hand-selected, in season, origin, variety, crisp, juicy, fragrant, fair price, นำเข้าเอง, คัดเอง, สดใหม่, ราคาที่จับต้องได้.

## Logo

The logo is a cargo ship carrying fruit. The fruit "sails" (cherry, apple, grapes, strawberry, orange) stand for the range, the flag for import, the round sun for daylight freshness, and the ripple lines for the port. In the wordmark, **FRESH** is heavy and **PORT** is regular. All the files are exact vectors from the official artwork: `Fresh Port copy.pdf` and `Fresh Port (แบบวงกลม) copy.pdf`.

- **Primary logo:** the white ship and wordmark on a `midnight-blue` ground. Use it wherever the logo stands on its own: social avatars, the Instagram corner tab, signage, packaging, the website header and footer.
  - `fresh-port-logo-primary`: stacked, square tile.
  - `fresh-port-logo-primary-horizontal`: horizontal.
  - `fresh-port-seal-primary`: circle seal.
  - `fresh-port-mark-primary`: ship-only app icon.
- **On light grounds** (`white`, `sea-mist`, `sail-cream`, light photos), where the white logo would disappear, switch to the midnight-blue ship: the `-navy` files, transparent.
- **On navy or dark photos without a tile,** use the `-white` files, transparent.
- **The logo has only two inks,** midnight blue `#112331` and white. There is no gold or other colour version.

| Lockup | Files | Use it for | Minimum size |
|---|---|---|---|
| Stacked | `fresh-port-logo-primary`, `fresh-port-logo-stacked-navy`, `-white` | Avatars, packaging, signage, footer | 90px / 24mm wide |
| Horizontal | `fresh-port-logo-primary-horizontal`, `fresh-port-logo-horizontal-navy`, `-white` | Website header, fascia, letterhead, the Instagram corner tab | 120px / 30mm wide |
| Port Seal | `fresh-port-seal-primary`, `-navy`, `-white` | Pack stickers ("PREMIUM QUALITY IMPORTED PRODUCTS"), hanging sign, gift boxes, LINE/Google profile | 60px / 15mm |
| Ship mark | `fresh-port-mark-primary`, `-navy`, `-white` | Favicon, app icon, small stickers, only where "Fresh Port" already appears nearby | 24px / 8mm |
| Wordmark | `fresh-port-wordmark-navy`, `-white` | Crate stencils, narrow banners, tape | — |

- **Clear space** equals the height of the round sun (about 1/8 of the stacked logo's height) on all sides. The files already include it.
- **On busy photos,** use the corner tab (Graphic elements) rather than placing the logo straight on the image.
- **Don't** retype the wordmark, or stretch, skew, rotate, outline, shadow or glow the logo. Don't recolour it, and don't change or rearrange the fruit.

## Colour

- **Midnight Blue is the constant.** Navy is about 60% of every surface: the header, hero, navy sections, profile slides and the corner tab. Pair it with white (website), cream (profile) or photography (Instagram).
- **Build with the semantic tokens,** not the palette. Use `surface`, `surface-alt` and `surface-raised` for grounds, `ink` and `ink-muted` for text, `line` and `line-soft` for borders, and `action`, `action-hover` and `on-action` for buttons. Switch a block's theme with `data-theme`:
  - `light`: the website.
  - `dark`: navy sections and navy slides.
  - `cream`: the business profile's light slides.
- **Where gold goes:**
  - **Business profile:** gold is the accent. `highlight` colours the second half of a headline and the italic English line, `accent` colours small-caps labels, rules and check icons, and harbour-gold fills badges and the long-term banner. Text on a gold fill is `on-gold` (7.9:1).
  - **Website:** stays navy and white, with gold only as a thin `accent` rule.
  - **Everywhere:** never set harbour-gold text on white (2:1).
  - **Gold sheen:** a 100° gradient from gold-deep through #f3e2b3 to harbour-gold, used only on the profile's one hero number and the long-term banner.
- **Small gold text on cream fails contrast.** gold-deep on cream is 2.8:1, and the profile uses it for 15px labels and 20px eyebrows. Keep it to labels that repeat what the headline says, and never use it for body text. On navy, harbour-gold passes (7.9:1).
- **Fruit colours come from the Instagram posts.** Use them only for product content: the fruit word in a headline, and the price blob behind the price. Each token's note names its posts. `price-secondary` is the bundle price circle, and `price-promo` is the offer tag.
- **White on the pale fruit fills fails contrast.** `fruit-orange`, `fruit-pear`, `fruit-plum` and `fruit-yellow` fall below 3:1 with white; set new prices on them in `midnight-blue`.
- **Other rules:**
  - Corner-tab stripes (`stripe-*`) are decorative and never carry text.
  - `status-open` is only a dot beside the word Open.
  - `crate-pine` is for wood and kraft surfaces.

## Type

- **Website:**
  - **Headings:** DM Serif Display 400 with -0.01em tracking (`display-hero`, `heading-2`, `display-sm`, `fruit-name`, `quote`, `step-number`). English only, with the Thai line under it in Prompt Light (`hero-thai`, `thai-sub`).
  - **Text:** Prompt for everything else (`body` 17px/1.7, `lede`, `card-title`, `faq-question`, `button`, `caption`, `eyebrow`, `label-caps`).
  - **Load:** `family=DM+Serif+Display&family=Prompt:wght@300;400;500;600`.
- **Business profile:**
  - **Headlines:** Thai first, in Prompt SemiBold (`profile-cover-title` 86px, `profile-title` 60px), with the English line in DM Serif Display Italic (`profile-en`).
  - **Numbers:** DM Serif Display (`profile-stat`, `profile-kpi`).
  - **Labels:** small caps with .16em tracking (`profile-label`, `profile-eyebrow`).
  - **Load:** `family=DM+Serif+Display:ital@0;1&family=Prompt:wght@400;500;600;700`.
- **Instagram:**
  - **Headlines:** DM Serif Text with the faux-bold outline (`ig-headline`, `ig-headline-fruit`).
  - **Price and unit:** Poppins (`ig-price`, `ig-unit`, `ig-handle`).
  - **Thai names:** Prompt Light (`ig-thai-pill`).
  - Details are in the Instagram section.
- **Bilingual pattern:**
  - Website: English headline, then a Thai light line.
  - Business profile: Thai headline, then an English italic line.
  - Thai is always Prompt, because the serif faces have no Thai.
- **The logo type is outlined artwork.** Never retype FRESH PORT; place the logo file.

## Layout, shape and depth

- **Website:**
  - Content width `container` (1180px); gutter `space-md`–`space-xl`; section padding 60px–`space-section`.
  - A sticky navy header, `header-height` tall, with the white horizontal logo at 44px; it takes `shadow-header` after scrolling.
  - A full-bleed hero photo under a left-to-right navy gradient (96% → 10%), with the highlights bar overlapping its bottom edge by 72px.
  - Sections alternate white, `sea-mist` and navy.
- **Business profile:**
  - 1920 × 1080 slides (`slide-width`) with `slide-margin` (110px) on both sides.
  - The logo and a small-caps slide label sit top-right, and a navigation bar sits at the bottom.
  - Slides alternate `dark` and `cream`.
- **Corners:**
  - `radius-card` (16px) for website cards.
  - `radius-panel` (26px) for large panels and feature images.
  - `radius-slide-card` (24px) for profile cards.
  - `radius-tile` (14px) for small profile tags.
  - `radius-icon` (12–13px) for icon tiles.
  - `radius-pill` for buttons, chips and pills.
- **Shadows** are always navy-tinted, never grey:
  - `shadow-sm` at rest and `shadow-md` on hover and for feature media.
  - `shadow-float` for the highlights bar.
  - `shadow-card-profile`, with `shadow-lift` on hover, on cream slides.
  - `shadow-gold` under gold nodes on navy.
- **Focus:** a 3px `focus-ring` outline, offset 3px.

## Motion

Motion is calm and long, from `fp-motion.css`:

- **Reveals:** fade and rise 40px (56px sideways for alternating media) over 0.9–1.1s on `cubic-bezier(.16,1,.3,1)`, staggered 90ms per item.
- **Images:** feature images unmask with a clip-path over 1.3s.
- **Hero:** the photo settles from 112% scale over 2.4s.
- **Header:** hides on scroll down and returns on scroll up, with a 2px reading-progress line.
- **Hover:** buttons pop 2px (`cubic-bezier(.34,1.56,.64,1)`), and cards lift 5px.
- **Business profile:** slides change with a wipe, an iris or a diagonal (`cubic-bezier(.77,0,.18,1)`, about 1.1s), and a gold light sweep rides the edge.
- **Reduced motion:** turns all of this off.

## Components

Static previews, hand-written from the live theme CSS and the deck stylesheet. Their styles are in `components/bundle.css`, which reads everything from tokens.

- **Website:** Button, Badge, SectionHead, HighlightsBar, FruitCard, PromisePoints, StepCard, PartnerCard, FAQ, VisitBlock.
- **Business profile:** SlideHeading, StatBlock, Timeline, FormatCard, ContactRow, ProfilePills.
- **Instagram:** ProductPost.

## Instagram product posts

Every product post is 1080 × 1350 (4:5), with a studio photo on a light backdrop and navy cloth. The Graphic elements group holds each piece as a vector, traced from and checked against the posts. Place them at these positions (post pixels):

1. **Corner tab** (`corner-tab-<fruit>`): 238 × 160 at the top-right corner (x 842, y 0). It is a `midnight-blue` wave with the white horizontal logo and a pastel `stripe-*` wave under it, picked to match the fruit. Store and announcement posts use `corner-tab-plain`.
2. **Headline:** two lines. The variety goes first, in `midnight-blue` (`ig-headline`). The fruit word goes second, larger, in its `fruit-*` colour (`ig-headline-fruit`). The headline sits in the upper third, centred or left-aligned, depending on where the photo is clear.
3. **Thai name pill:** directly under the headline. Thai name in `ig-thai-pill`, 1px `midnight-blue` outline, full radius, about 150 × 41.
4. **Origin stamp** (`origin-stamp-<country>`): a white disc about 200px across, set on the pack or crate.
   - The top text reads "Freshly imported from", with the flag in the middle and the country along the bottom.
   - Thai produce reads "Freshly from" instead.
   - Available for Chile, USA, Australia, New Zealand, China, Japan, Korea and Thailand.
5. **Price blob:**
   - `price-blob-corner` bleeds off the bottom-left corner (335 × 307 at x 0, y 1043).
   - `price-blob-float` (about 320 × 235) or `price-blob-round` floats over the photo.
   - Recolour the fill to the fruit's `fruit-*` token. Set the price in `ig-price` with the unit line in `ig-unit` centred under it. A second, bundle price goes in a smaller `price-secondary` circle.
6. **LINE pill** (`line-pill`): 291 × 39, bottom centre (x 390, y 1281), a white pill with the LINE icon and "@freshport".

The Instagram posts group holds the 35 original posts for reference. When in doubt, match them.

## Graphic elements and imagery

- **Photography** (Photography group):
  - Bright daylight on a white or `sea-mist` backdrop, navy cloth under the fruit, pine crates stencilled FRESH PORT, and glossy fruit in sharp focus.
  - Real staff, not stock models.
  - Avoid heavy filters, dark moody shots and bruised fruit.
- **Ripple lines** are always horizontal, with rounded ends, 3–5 bars of varying length.
- **Watermark ship:** the ship mark on navy at 4–6% opacity.
- **Profile maps:** a dotted world map at 9% white, with gold arcs flowing into Thailand.

## Iconography

- **Line icons:** the Icons group holds the website's 14 icons (24px grid, 1.8 stroke, round joins). Use them at 22px in 44–46px tiles: `sea-mist` tiles with navy icons on light grounds, and navy or translucent tiles with white icons on navy.
- **Business profile icons:** the same icons in gold inside navy tiles.
- **Social icons:** social networks keep their own brand-coloured tiles in the profile's contact rows.
- **Flags:** flags mark the origin and appear only inside an origin stamp.

## Not synced

- **Sources:** the live Shopify theme ('Fresh Port Landing — SEO + navy favicon') and the business-profile deck files (`fpd-src-*`), which were read only; nothing in Shopify was changed. Also the Brand Identity Guide, the Instagram posts and the official logo PDFs.
- **GitHub:** this system is exported for the repository `vegastrp47-design/freshport` under `design-system/`, with the tokens compiled to `tokens/tokens.css`, standalone component previews and an `index.html` overview. The repository held only a README at commit 7e2338a, so nothing was synced from it.
- **Deck mismatches:** the deck's `--navy-2 #18314a`, `--navy-3 #23415e` and `--muted #5d6b78` differ slightly from the website. The website values were kept.
- **Not included:**
  - Partner and grower logos, which belong to those brands.
  - The V.S.M. Fruit mark.
  - The deck's floor-plan and map illustrations.
  - Coded React components (the previews are static).
  - Font files, because all faces are hosted on Google Fonts.
- **LINE icon:** the icon inside `line-pill` is copied from the posts at post resolution. For print, use LINE's official icon.
