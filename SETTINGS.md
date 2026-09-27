# Opal settings

Open **Settings → Style Settings → Opal** to find these 83 controls. The names below match the English interface. Style Settings also provides Simplified Chinese titles and descriptions, while choice menus use bilingual labels.

These controls change the appearance across your vault. The [README](https://github.com/cyriusweng/opal-theme#style-individual-notes-with-opal-companion) explains per-note styles. Colours with separate light and dark defaults can be changed independently. Font names refer to fonts available on your device.

## Colours

| Setting | Default | What it changes |
| --- | --- | --- |
| Primary accent colour<br>`opal-accent` | Light `#4C50C8`; dark `#8098FF` | The main accent for controls, focus indicators and background glow. Standard links use the palette blue; per-note accent classes can recolour internal links. |
| Secondary accent colour<br>`opal-accent-2` | Light `#127367`; dark `#82D9C8` | A secondary accent used for supporting highlights and the other end of gradients. Defaults to teal. |
| Accent saturation<br>`opal-accent-saturation` | `1` | 1 keeps the original colour. Lower values are greyer and quieter; higher values are more vivid. Older engines ignore this setting. Range `0.4` to `1.6`, in steps of `0.05`. |
| Light theme tint<br>`opal-tone-light` | Light `#EDEFF4`; dark `#EDEFF4` | The tint mixed into light backgrounds. Choose peach for warm grey, blue for cool grey, or violet for purple-grey. The strength setting below controls the amount. |
| Dark theme tint<br>`opal-tone-dark` | Light `#20232E`; dark `#20232E` | The tint mixed into dark backgrounds. The strength setting below controls the amount. |
| Background tint strength<br>`opal-tone-strength` | `0%` | How much of the selected tint is mixed into backgrounds. 0 keeps the default background colours; higher values mix in more of the tint. Range `0%` to `18%`, in steps of `1%`. |
| Surface contrast<br>`opal-surface-contrast` | `100%` | The brightness difference between the document background and surfaces such as sidebars and cards. 100 gives the normal layering; lower values look flatter. Range `40%` to `100%`, in steps of `5%`. |
| Code block background<br>`opal-code-bg` | Light `#E2E5EE`; dark `#2B2F3C` | The background fill behind code blocks. |
| Highlight colour<br>`opal-mark-bg` | Light `#F6E1A2`; dark `#EBD08A` | The colour used by the chosen highlight style, including the default wavy underline. |
| Highlight style<br>`opal-mark-style` | Neon wave | Choose a wavy underline, solid background, soft background or coloured text. The menu calls the underline Neon wave and the coloured-text option Neon text. Choices are Neon wave, Solid highlight, Soft highlight, Neon text. |
| Heading colour scheme<br>`opal-heading-scheme` | Rainbow | Give each heading level a different colour, use shades of one colour, use the shared indigo accent, set each level separately, or follow the body text colour. Choices are Rainbow, Monochrome gradient, Single accent, Custom by level, Body text colour. |
| Tag colour scheme<br>`opal-tag-scheme` | First-letter pseudo-hash | Colour tags by groups of first letters, by recognised keywords, or with one colour. Choices are First-letter pseudo-hash, Semantic keywords, Single colour. |
| Unresolved link style<br>`opal-unresolved-link` | Dashed underline | Set the appearance of links to notes you may create later. Choices are Dashed underline, Muted, Blurred, Question badge. |

## Fonts

| Setting | Default | What it changes |
| --- | --- | --- |
| Body font<br>`opal-font-text` | `Inter` | Enter an installed font name, or separate several names with commas. The fallback list includes system fonts for Chinese, Japanese and Korean. |
| Heading font<br>`opal-font-heading` | `Inter` | The font used for headings. Keep Inter or enter a display font. |
| Code / monospace font<br>`opal-font-code` | `JetBrains Mono` | The font used for code and other monospaced text. |
| Interface font<br>`opal-font-ui` | `Inter` | The font used in sidebars, menus, tabs, and other interface elements. |
| Body font size<br>`opal-font-size` | `16px` | The size of ordinary note text. Range `12px` to `22px`, in steps of `1px`. |
| Body line height<br>`opal-line-height` | `1.5` | Space between lines, measured as a multiple of the text size. Range `1.2` to `2.2`, in steps of `0.05`. |
| Body letter spacing<br>`opal-letter-spacing` | `0px` | Extra space between letters. Range `-0.5px` to `2px`, in steps of `0.1px`. |
| Uncoloured bold text<br>`opal-uncolored-bold` | Off | Bold text is peach by default. Enable this to keep the body colour and change weight only. |
| Code font features<br>`opal-font-features` | `normal` | Advanced. Enter OpenType features such as "liga" 1, "calt" 1 for ligatures, or "zero" 1 for a slashed zero. Keep normal for the font default. |

## Heading levels

| Setting | Default | What it changes |
| --- | --- | --- |
| H1 size<br>`opal-h1-size` | `2em` | Size of level-one headings relative to the body text. Range `0.9em` to `3.2em`, in steps of `0.05em`. |
| H2 size<br>`opal-h2-size` | `1.65em` | Size of level-two headings relative to the body text. Range `0.9em` to `3em`, in steps of `0.05em`. |
| H3 size<br>`opal-h3-size` | `1.4em` | Size of level-three headings relative to the body text. Range `0.9em` to `2.6em`, in steps of `0.05em`. |
| H4 size<br>`opal-h4-size` | `1.2em` | Size of level-four headings relative to the body text. Range `0.9em` to `2.2em`, in steps of `0.05em`. |
| H5 size<br>`opal-h5-size` | `1.1em` | Size of level-five headings relative to the body text. Range `0.9em` to `2em`, in steps of `0.05em`. |
| H6 size<br>`opal-h6-size` | `1em` | Size of level-six headings relative to the body text. Range `0.8em` to `1.8em`, in steps of `0.05em`. |
| H1 weight<br>`opal-h1-weight` | `700` | Weight of level-one headings. Higher values make the letters heavier. Range `100` to `900`, in steps of `50`. |
| H2 weight<br>`opal-h2-weight` | `700` | Weight of level-two headings. Higher values make the letters heavier. Range `100` to `900`, in steps of `50`. |
| H3 weight<br>`opal-h3-weight` | `650` | Weight of level-three headings. Higher values make the letters heavier. Range `100` to `900`, in steps of `50`. |
| H4 weight<br>`opal-h4-weight` | `600` | Weight of level-four headings. Higher values make the letters heavier. Range `100` to `900`, in steps of `50`. |
| H5 weight<br>`opal-h5-weight` | `600` | Weight of level-five headings. Higher values make the letters heavier. Range `100` to `900`, in steps of `50`. |
| H6 weight<br>`opal-h6-weight` | `600` | Weight of level-six headings. Higher values make the letters heavier. Range `100` to `900`, in steps of `50`. |
| Heading underline<br>`opal-hd-line` | Gradient underline | The line beneath headings. It can be combined with the heading prefix below. Choose a per-level gradient, a single underline, or none. Choices are Gradient underline, Single underline, None. |
| Heading prefix<br>`opal-hd-prefix` | None | Add hanging hash marks to rendered headings, or automatically number H2 and H3 headings in Reading view. Choices are None, Hanging hash, Automatic numbering. |
| H1 colour (custom scheme)<br>`opal-h1-color` | Light `#4C50C8`; dark `#A6A8F2` | Level-one heading colour when Heading colour scheme is set to Custom by level. |
| H2 colour (custom scheme)<br>`opal-h2-color` | Light `#1E69A1`; dark `#86BFF0` | Level-two heading colour when Heading colour scheme is set to Custom by level. |
| H3 colour (custom scheme)<br>`opal-h3-color` | Light `#0E6E82`; dark `#82CFE6` | Level-three heading colour when Heading colour scheme is set to Custom by level. |
| H4 colour (custom scheme)<br>`opal-h4-color` | Light `#127266`; dark `#82D9C8` | Level-four heading colour when Heading colour scheme is set to Custom by level. |
| H5 colour (custom scheme)<br>`opal-h5-color` | Light `#5C6B1B`; dark `#C6D98A` | Level-five heading colour when Heading colour scheme is set to Custom by level. |
| H6 colour (custom scheme)<br>`opal-h6-color` | Light `#B13A56`; dark `#F08AA0` | Level-six heading colour when Heading colour scheme is set to Custom by level. |

## Layout and sizing

| Setting | Default | What it changes |
| --- | --- | --- |
| Readable line width<br>`opal-line-width` | `700px` | Maximum width of the note's text column. Range `400px` to `1400px`, in steps of `20px`. |
| Full-width tables<br>`opal-table-widen` | Off | Make tables use the full available width instead of limiting them to the readable line width. |
| Scroll wide diagrams horizontally<br>`opal-mermaid-scroll` | Off | Keep wide Mermaid diagrams at their original size and allow horizontal scrolling. |
| Paragraph spacing<br>`opal-para-spacing` | `16px` | The gap between paragraphs. Range `0px` to `40px`, in steps of `2px`. |
| First-line indent layout<br>`opal-first-indent` | Off | Indent the first line of each Reading-view paragraph and close the gap between paragraphs. |
| List indentation<br>`opal-list-indent` | `2em` | How far each nested list level is indented. Range `0.8em` to `4em`, in steps of `0.1em`. |
| Editor vertical margins<br>`opal-file-margin` | `40px` | Space above and below the note content. Range `0px` to `120px`, in steps of `5px`. |
| Image corner radius<br>`opal-img-radius` | `10px` | Rounding at the corners of images. Range `0px` to `30px`, in steps of `1px`. |
| Maximum image width<br>`opal-img-width` | `100%` | Maximum image width as a share of the available space. Range `30%` to `100%`, in steps of `5%`. |
| Image shadow<br>`opal-img-shadow` | Off | Add a soft shadow that makes images appear slightly raised. |
| Editor background texture<br>`opal-bg-texture` | None | Add dots, a square grid or ruled lines behind the note. Choices are None, Dot grid, Square grid, Ruled lines. |
| Corner radius<br>`opal-radius` | `10px` | Rounding at the corners of interface elements. Range `0px` to `20px`, in steps of `1px`. |
| Corner shape<br>`opal-corner` | Squircle | Squircle gives a softer iOS-style corner and falls back to standard rounding on older engines. Rounded, scoop, and bevel shapes are also available. Choices are Squircle, Rounded, Scoop, Bevel. |

## Borders and dividers

| Setting | Default | What it changes |
| --- | --- | --- |
| Global border width<br>`opal-border-width` | `1px` | One shared stroke width for cards, inputs, tables, menus, and other outlined elements. Range `0px` to `3px`, in steps of `0.5px`. |
| Global border colour<br>`opal-border-color` | Light `#D3D8E3`; dark `#3A3F4E` | The shared colour for borders and dividers. |
| Divider style<br>`opal-divider-style` | Fade | Set the appearance of Markdown horizontal rules. Choices are Fade, Solid, Dashed, Dotted, Double. |
| Panel divider borders<br>`opal-pane-borders` | Off | Draw divider lines between adjacent panes. The default uses spacing alone to separate them. |
| File tree indentation guides<br>`opal-nav-indent-line` | On | Draw a vertical guide for each indentation level in the file tree. Enabled by default. |
| List indentation guides<br>`opal-indent-guide` | Off | Draw vertical guides through nested lists in documents. Disabled by default. |
| Focus ring style<br>`opal-focus-ring` | Outline | Show an outline or glow when a control receives keyboard focus. Choices are Outline, Glow, None. |
| Scrollbar width<br>`opal-scrollbar-width` | `12px` | The thickness of scrollbars. Range `0px` to `18px`, in steps of `1px`. |
| Table borders<br>`opal-table-border` | Horizontal rules | Choose Horizontal rules, Full grid or Borderless. The Horizontal rules preset retains native vertical cell borders in Obsidian 1.13.7. |

## Element toggles

| Setting | Default | What it changes |
| --- | --- | --- |
| Remove link underlines<br>`opal-link-plain` | Off | Remove link underlines and distinguish links by colour alone. |
| Wrap code blocks<br>`opal-code-wrap` | Off | Wrap long code lines instead of scrolling horizontally. |
| Code ligatures<br>`opal-code-ligatures` | Off | Enable programming ligatures when the selected code font supports them. |
| Disable table stripes<br>`opal-table-plain` | Off | Remove the subtle fill used on alternating table rows. |
| Highlight active line<br>`opal-active-line` | Off | Add a faint accent background to the line containing the cursor. |
| Focus mode<br>`opal-focus-mode` | Off | Dim editor lines around the current line. |
| Use native checkboxes<br>`opal-tasks-native` | Off | Use Obsidian's native checkbox appearance instead of Opal's custom task states. |
| List markers<br>`opal-list-scheme` | Hierarchical shapes | Choose different shapes by list depth, colours by depth, or a single filled dot. Choices are Hierarchical shapes, Rainbow cycle, Single-colour dots. |
| Disable ambient background glow<br>`opal-no-bg-orb` | Off | Remove the faint ambient glow behind the editor. |

## Skins and motion

| Setting | Default | What it changes |
| --- | --- | --- |
| Surface material<br>`opal-surface` | Opaque solid | Choose solid or translucent menus and popovers. The glass options add background blur. Reduced transparency switches both glass styles to solid. Choices are Opaque solid, Frosted glass, Liquid glass. |
| Interface design language<br>`opal-ui-language` | Neutral | Change control shapes, borders and shadows. Cupertino uses rounder controls, Fluent adds light borders, and Material uses squarer corners and stronger shadows. Choices are Neutral, Cupertino, Fluent, Material. |
| Callout skin<br>`opal-callout-skin` | Fused (soft fill + side bar) | Choose a shaded card with a side line, a hard shadow, an outline, a glowing border, a coloured title bar or a folded corner. Choices are Fused (soft fill + side bar), Brutalist shadow, Minimal outline, HUD glow, Inverted title bar, Folded paper. |
| Folder colours<br>`opal-folder-scheme` | Rainbow spine | Rainbow spine gives each top-level branch a colour inherited by its children. Numbered sections colour names starting with `00`, `10`, `20` and `90`. Choices are Rainbow spine, Numbered sections, Single colour, Off. |
| Motion level<br>`opal-motion` | Standard | Set the pace of interface animations. Subtle is slower, Lively is quicker and springier, and Off disables animations and transitions. The system's reduced-motion setting also shortens them. Choices are Off, Subtle, Standard, Lively. |
| Page entrance<br>`opal-entrance` | Focus from blur | Choose how a newly opened note appears, using blur, a small upward slide or a bounce. Choices are Focus from blur, Smooth slide, Elastic overshoot. |
| Retro skin<br>`opal-retro` | None | Change the palette to Synthwave, green phosphor, amber CRT or Digital rain. Choices are None, Synthwave, Green phosphor terminal, Amber CRT, Digital rain. |

## Print and PDF export

| Setting | Default | What it changes |
| --- | --- | --- |
| Keep dark colours in exports<br>`opal-print-dark` | Off | Exports use a white paper background by default. Enable this to preserve the dark theme, and enable background printing in the export tool. |
| Print body font<br>`opal-print-font` | Serif | Choose a serif font, keep the note's current font, or use a monospaced typewriter style. Choices are Serif, Keep current font, Typewriter. |
| Print paragraph alignment<br>`opal-print-align` | Justified | Choose book-style justified paragraphs with first-line indentation, or left-aligned paragraphs. Choices are Justified, Left aligned. |
