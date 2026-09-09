---
name: brand-exploration
description: Create a complete brand exploration board as one composed landscape image from an uploaded logo, with logo treatments, typography, palette, icons, photography, patterns, moodboard, mockups, and CTAs. Use for brand moodboards or style tiles grounded in an existing logo; not for unrelated logo redesigns.
---

# Brand Exploration

Act as a senior brand identity designer. Read the uploaded logo's visual language and create a professional agency-quality exploration board as **one composed image**. This is an early branding presentation, not a production brand manual. The user's specific changes override these defaults.

## Input and visual direction

- A usable logo image is required. If it is missing or inaccessible, ask for it and wait: “Загрузите логотип — я соберу единый Brand Exploration board.” Do not generate an invented substitute. Otherwise proceed without a default questionnaire.
- Inspect the actual image before designing. For a local image, use the available image viewer. Supply the logo itself as an image reference to the generation tool through its supported reference mechanism; a written description alone is insufficient. Use any supplied context or brand name, but do not guess unreadable lettering.
- Identify observable geometry, proportions, stroke character, spacing, colors, and typographic personality. Derive a coherent direction from those features. Separate proposed associations from known facts: a precise geometric mark may suggest precision, but does not establish the company's industry, audience, history, or values.
- Preserve the logo's identity in every appearance: exact mark structure, proportions, orientation, negative space, lettering, and lockup. Change only color treatment or the perspective/lighting needed to apply the mark to a mockup. Do not redesign, add symbols, substitute a similar logo, or invent a tagline.
- Use the original visual language to choose every palette, font pairing, icon style, photographic mood, pattern, and mockup. When context is sparse, choose broadly applicable surfaces and visual associations instead of inventing a business sector.

## Required board content

Include all nine sections with these exact English headings by default. Use the user's requested language if they explicitly ask for localization. Keep the quantities exact where a fixed number is specified.

| Section heading | Required content |
| --- | --- |
| LOGO VARIATIONS | **4** presentations of the supplied mark: original full color, black, white/reversed on a dark field, and one alternative color treatment. Preserve the same mark and lockup in all four. |
| TYPOGRAPHY EXPLORATION | **6** suitable font pairings in a **2-column × 3-row grid**. Each tile names both font families, shows **“BRAND NAME”** large in the proposed primary style, and **“Tagline / Descriptor”** smaller in the secondary style. Use a supplied brand name instead of the placeholder only when requested. Choose real, correctly named font families; do not invent font names. The generated lettering is a visual approximation of the proposed pairing, not proof that the exact font files were rendered. |
| COLOR PALETTE | **5–6** coherent swatches derived from or complementary to the logo, each with its hexadecimal code underneath. Include at least one dark, one light/neutral, and one accent. Choose the codes before generation and reuse them consistently. Treat visually estimated source colors as estimates unless actually sampled. |
| BRAND ELEMENTS / ICONS | **5** minimal flat icons with a consistent stroke or fill style. Each represents a proposed value suggested by the logo and has a **one-word label**. Do not claim these are the company's declared values. |
| BRAND IMAGERY | **One row of 5** photographic mood images that match the brand's aesthetic. Use realistic photography style, not illustrations or cartoons. Generated photography is acceptable; do not present it as commissioned or sourced real-world photography. |
| PATTERN & TEXTURE | **4** distinct pattern or texture swatches suitable for brand backgrounds or materials, related to the mark's geometry, palette, and visual character. |
| MOODBOARD | **6–8** tightly cropped inspirational images showing atmosphere, materials, lighting, and plausible context. Keep these image interiors free of text overlays. The section heading sits outside them. |
| BRAND IN ACTION | **2–3** realistic mockups with the actual logo visibly applied, such as a website header, business card, phone screen, or signage. Choose surfaces consistent with available brand evidence; preserve logo identity and credible scale/perspective. |
| CALL TO ACTION EXAMPLES | **4** button/CTA examples using the board's colors and one selected proposed font pairing. Include both filled and outlined variants. Use short, readable, generic action labels unless the user supplies copy. |

Keep BRAND IMAGERY and MOODBOARD as distinct sections with their own required image counts. Do not silently merge sections or replace the complete board with several separate outputs.

## Layout and generation

1. Build a compact internal design brief from the observed logo. Decide the font-pair names, 5–6 hexadecimal colors, five icon labels, four CTA labels, and the counts selected within the allowed ranges before generating. Keep this brief consistent throughout the board.
2. Compose one wide landscape canvas, approximately **1600 × 1000 px**, with the nearest supported landscape dimensions if necessary. Prioritize readable content and preserve the whole composition; do not crop sections to force exact dimensions. Use a clean white or near-white background, aligned modules, intentional whitespace, and small-caps, letter-spaced dark-gray section headings. Anchor the logo area on the left, with exploration content on the right and below. Allocate ample space to the six typography tiles and avoid tiny labels.
3. Use the host's **built-in image-generation tool** when available. Include the actual logo reference, the visual brief, all nine section specifications and counts, exact text, layout rules, and logo-preservation constraints in the generation request. Identify the logo as the identity reference, not merely a style reference. Follow the active tool's supported image-reference arguments; do not assume a filename mentioned in the prompt has attached the image.
4. Generate the full board as one image. Do not replace the requested photographic board with a text-only report, an unexecuted prompt, or code-drawn placeholders. Do not silently call a paid API, require an API key, or switch providers. If built-in generation is unavailable or fails, explain the limitation briefly and offer an explicitly authorized fallback; do not claim an image was created.

## Review and delivery

Inspect the returned image if the environment permits. Check the complete composition at normal view and the dense areas at useful detail:

- All nine headings and required item counts are present, with no missing or duplicated section.
- Every logo appearance is recognizably faithful to the source; no distorted symbol, changed lettering, or invented brand name appears.
- Font family names, specimen text, hexadecimal codes, icon labels, and CTA labels are readable and spelled as specified. The typography grid contains six distinct pairings.
- The palette is used consistently; each code matches its intended swatch as closely as the raster generation allows. Reversed logos and CTA labels are visible on their backgrounds.
- The photographic rows have the correct counts and medium. Moodboard crops have no text overlays. Mockups visibly apply the supplied logo and have plausible perspective.
- The board feels like one coherent design direction, with clean alignment and sufficient whitespace rather than nine unrelated collages.

If a material defect is visible, make a targeted image edit and recheck; restate the original identity constraints and reference the original logo during corrections to limit drift. Preserve successful sections. Limit automatic correction to **two** attempts, then deliver the best available result with a short description of any unresolved material defect. Do not claim pixel-perfect logo preservation or exact font rendering from generated pixels. If inspection is unavailable, do not claim the board passed visual checks.

Return **one final board image**, preferably inline, with a downloadable file/link when available. For a workspace deliverable, retain a copy in the user's chosen output location or the project workspace without overwriting source files. Keep accompanying prose brief and in the user's language: at most a short sentence about the direction and any material limitation. Do not add a long branding analysis, additional variants, or claim exact image dimensions that have not been verified.
