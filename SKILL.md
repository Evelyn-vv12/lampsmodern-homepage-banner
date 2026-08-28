---
name: lampsmodern-homepage-banner
description: Plan, research, write, generate, and archive LampsModern UK homepage hero/banner campaigns. Use when the user says the homepage banner needs changing, asks for a new homepage banner theme, or asks to continue the homepage banner workflow. This skill covers only the top homepage hero/slideshow banners, not the whole homepage and not EDM banners.
license: private
metadata:
  owner: Evelyn
  brand: LampsModern UK
  version: "1.0.0"
---

# LampsModern Homepage Banner Skill

## Scope

This skill is for the **top homepage hero/slideshow banner area only** — the two large homepage banner images.

Do not confuse this with:
- EDM banners
- homepage product/category modules
- full homepage redesign
- social media creatives

Default working mode: **two homepage banners per refresh**.

1. **Primary promotional banner**
   - carries the current promotional offer / discount code
   - normally uses a commercially important product category
   - should have the stronger conversion focus

2. **Secondary thematic banner**
   - supports a seasonal / weather / lifestyle / category story
   - normally does **not** show a discount code
   - should feel visually distinct from the primary banner

## Conversation protocol

When the user says things like:
- “首页 Banner 要换新的”
- “来新的”
- “这期 Banner 做什么”
- “给我两个 Banner 主题”

do not ask for a long checklist.

**Ask one question at a time only.**

The user prefers conversational requirement collection and should not need to remember multiple questions at once.

Do not ask for information that can be researched or inferred:
- current date
- next 10 days of UK weather
- nearby UK seasonal / retail moments
- current competitor promotions
- recent banner history
- current LampsModern category structure / sales context when available

## Time window

For each new homepage banner refresh, use:

**request date → next 10 days**

as the default planning window.

Research and judge:
- UK weather changes
- daylight / darker evenings
- rain / wind / indoor-vs-outdoor behaviour
- seasonal transition
- relevant UK holidays / retail moments
- current UK lighting/homeware promotion signals

The theme should match the real period rather than use a generic seasonal label.

## Decision inputs

Banner theme and hero category should be selected from multiple signals, not from one rule alone.

Use:
1. next-10-day UK weather and seasonal context
2. relevant UK events / retail calendar
3. current UK lighting/homeware competitor promotion patterns
4. current LampsModern category and sales structure when available
5. immediately previous homepage banner categories
6. visual freshness and scene suitability

Do not make “SEO trend” claims without evidence. If current market/SEO signals are unavailable, say so rather than inventing them.

## Category recording granularity

Never record only a broad label such as “Ceiling Lights”.

Record each banner as:

**Broad Category + Subcategory/Style + Scene**

Example:

**Ceiling Lights / Crystal Ceiling Lights / Living Room**

This prevents false “duplicate” judgments when two products share a broad category but have different visual and commercial roles.

## Category repetition rule

“Do not repeat” is **not** a permanent blacklist.

Default rule:
- avoid mechanically repeating the **immediately previous banner’s** hero category/subcategory
- older categories may be reused
- if the same category is clearly best because of weather, season, sales strength, promotion logic, or category importance, it may be repeated

When repeating a recent category, explicitly tell the user:

**“This repeats the previous category, but I still recommend it because…”**

and give the reason.

Do not force a weaker category purely for novelty.

## Commercial objective and discount logic

The homepage banner is normally a timely promotional/theme campaign.

Do **not** default the campaign objective to:
- clearance
- new arrivals
- “increase AOV” as the theme itself

New-arrival campaigns are uncommon unless explicitly relevant.

Clearance should only be used when there is a real stock / sale reason.

**AOV improvement belongs mainly in the discount structure**, not in the theme title.

When recommending codes:
- research current competitor promotion structures when current data is useful
- use competitor discounts as context, not as copy-paste templates
- prefer threshold / tiered offers when appropriate
- keep the entry threshold reachable
- use higher tiers to encourage larger baskets
- explain why the thresholds make sense

Never invent a competitor promotion and present it as current fact.

## Required copy structure

Every banner must have its own complete copy block:

1. **Main Title**
2. **Supporting Line**
3. **CTA**

Example only:

Main Title:
**A Brighter Welcome Home**

Supporting Line:
**Outdoor lighting for changing weather.**

CTA:
**Explore Outdoor Lighting →**

These example words are **not fixed templates**.

The title, supporting line, and CTA must be regenerated to fit the actual theme.

### CTA rule

CTA must:
- be short and action-oriented
- fit the actual category/theme
- include a right-pointing arrow in the visual treatment

Examples:
- Explore the Collection →
- Shop Ceiling Lights →
- Explore Outdoor Lighting →
- Shop the Sale →

Do not use the same CTA mechanically every time.

## Primary vs secondary banner content

### Primary promotional banner

Must include:
- Main Title
- Supporting Line
- discount / code structure
- CTA
- hero category
- scene direction
- separate standalone banner image

### Secondary thematic banner

Must include:
- Main Title
- Supporting Line
- CTA
- hero category
- scene direction
- separate standalone banner image

Default:
- no discount code
- no promotional date line

Only add a code if the user explicitly wants one.

## Visual system

The homepage image itself is **colour**, not black-and-white.

Default composition:
- realistic modern UK home setting
- premium but ordinary/livable, not luxury-showroom CGI
- product category clearly visible and appropriately installed
- strong, believable scene/product relationship
- left roughly **30%** reserved for copy
- left side uses a **translucent dark/black gradient overlay**
- the overlay must retain visible environmental detail underneath
- never use a fully opaque solid-black block unless explicitly requested
- white title/body copy by default
- image and page should feel compatible with LampsModern’s black/white website direction

The accent colour is flexible.

Do **not** default every campaign to gold.

Choose a restrained accent that matches the scene and still works with the site:
- muted blue
- soft rose
- subtle neutral
- restrained warm accent
- other low-saturation accent when justified

Avoid:
- cheap sale-poster styling
- constant gold accents
- excessive luxury styling
- excessive HDR / CGI cleanliness
- trust-icon rows inside the banner
- UK Delivery / Warranty / Easy Returns icons inside the banner
- dates such as “28 Aug – 7 Sep” inside the banner unless explicitly requested

## Image-generation rule — strict

**1 confirmed theme = 1 standalone banner image.**

Therefore:
- 1 theme → 1 image
- 2 themes → 2 separate image files

Never:
- stack two banners vertically in one image
- create a split comparison sheet as the final banner delivery
- combine the primary and secondary banner into one canvas

unless the user explicitly asks for a comparison board.

The generated image should already be close to usable and should contain:
- intended scene
- left translucent dark gradient
- Main Title
- Supporting Line
- CTA with arrow
- discount information only where appropriate

Do not give only a prompt when the user asked for the image.

## Output format for each refresh

Before generating images, provide the complete plan as **two independent banner sections**.

For each banner include:
- role: Primary Promotional / Secondary Thematic
- Main Title
- Supporting Line
- CTA
- Broad Category
- Subcategory / Style
- Scene
- discount structure if applicable
- why this category/theme fits the next 10 days
- recent-category repeat warning if applicable
- visual direction

Then generate:
- Banner 01 as its own image
- Banner 02 as its own image

Do not place all text for both banners into a single design-board image.

## Dimensions

Do not use EDM dimensions for homepage banners.

Do not automatically output dimensions to the user or designer.

If exact homepage dimensions are required:
- inspect the current live homepage hero/slideshow or user-provided current banner asset
- use the current homepage implementation as the reference
- do not guess from EDM sizes such as 600×512

## Historical record workflow

The repository history is used to remember what was used recently and to support better category rotation.

After the user clearly confirms the final pair, for example:
- “这期就确定这两个”
- “就用这两个”
- equivalent explicit confirmation

append both banners to:

`history/banner-history.md`

Record:
- date / period
- banner role
- Main Title
- Supporting Line
- CTA

When importing historical records from a spreadsheet or handoff, **preserve the source CTA exactly if it is provided**. Do not omit it, rewrite it, or infer a replacement unless the user explicitly asks for a copy update.
- broad category
- subcategory/style
- scene
- discount/code
- product URL if known
- rationale / notes
- repeat warning if relevant

History is a **decision reference**, not a permanent blacklist.

## Final quality check

Before delivery verify:

1. Only the top homepage hero/banner workflow is being handled.
2. Planning window is request date + next 10 days.
3. Current UK context was checked when it could materially affect the theme.
4. Category is recorded as broad + subcategory/style + scene.
5. Previous-banner repetition is treated as a warning, not a hard ban.
6. If a recent category is repeated, the reason is stated.
7. AOV logic is handled through offer structure, not theme wording.
8. Both banners have Main Title + Supporting Line + CTA.
9. Primary banner has the offer/code when relevant.
10. Secondary banner has no code by default.
11. Left overlay is translucent, not solid black.
12. Accent colour is not automatically gold.
13. No trust icons are added to the banner.
14. No date line is added unless requested.
15. **One theme equals one standalone image.**
16. Two themes are delivered as **two separate image files**.
17. Confirmed banners are written into banner history.
