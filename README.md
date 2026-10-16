# PagePatch — free HTML/CSS hero example

A single-file hero section for a fictional design-feedback product, with an intentionally weak before page and five explained changes. Open the HTML files directly in your browser; there is no build step.

**AI-generated code and explanations.** The business is fictional. These design changes are hypotheses, with no measured conversion improvement or customer results claimed.

[Try the live hero](https://pagepatch-fix-pack.p-lucas.chatgpt.site/sample-hero.html) · [See the before page](https://pagepatch-fix-pack.p-lucas.chatgpt.site/sample-before.html) · [Read the explanation](report.md) · [Edit the HTML/CSS in your browser](https://jsfiddle.net/k7um8q5w/)

## Use it

1. [Download the free sample ZIP](https://github.com/l-portet/pagepatch-free-hero/releases/download/sample-v1.0.0/pagepatch-free-worked-example.zip) (about 10 KB; no account or payment).
2. Unzip the download, then open `START-HERE.html` and choose `hero.html`.
3. Edit `hero.html` in a text editor. Replace the fictional product details with your own verified facts.
4. Copy the block marked `PAGEPATCH HERO` and its scoped `.pp-*` styles into your page, then replace action links with your real destinations.
5. Check the integrated page at narrow widths, with keyboard navigation, and at 200% text zoom. Basic HTML/CSS skills are needed.

No JavaScript, external fonts, libraries, tracking, or installation is included in the sample.

### Editing the action row in a visual layout tool

In an October 15, 2026 test, Layout Forge imported the `.pp-actions` container settings but omitted both anchor children when given the sample's HTML. Importing only the `.pp-actions`, `.pp-action` and `.pp-secondary` CSS produced two editable layout blocks. The [tested workaround and editable demonstration](https://github.com/vumox/layout-forge/issues/15#issuecomment-6191611118) show the result and its limits.

Use that model to explore wrapping and gaps. Its export uses generic `div` elements and simplifies the original padding; it does not retain the working links, labels or complete appearance. Keep the original `<a href="#example">` and `<a href="#workflow">` elements in `hero.html`, and copy back only the layout declarations you intend to change. Preserve the `:focus-visible` rules, then Tab to each link and press Enter to check its destination after editing.

This was an agent-run editing test, not customer feedback or an endorsement by Layout Forge. The sample's source is unchanged.

## What changed

| Before | Proposed change |
| --- | --- |
| Abstract headline | Identify the task and product |
| “Get started” without a clear destination | Label the action “See an example review” |
| Generic adjectives | Explain the workflow in concrete steps |
| Three equally prominent calls to action | One primary action and one secondary link |
| Fixed-width container and removed focus outline | Fluid layout and visible keyboard focus |

The [report](report.md) includes the reasoning, boundaries, and suggested validation. `before.html` intentionally contains problems for comparison; use `hero.html` as the starting point. This is an educational example, not an accessibility certification or a production audit.

## Files

- `hero.html` — editable proposed hero with working local section links.
- `before.html` — intentionally weak fictional source page.
- `report.md` and `report.html` — five findings and implementation guidance.
- `START-HERE.html` — browser-friendly navigation and instructions.
- `LICENSE.txt` — the original free-sample reuse permission.

## Reuse

You may use, modify, and redistribute the original sample commercially. Attribution is not required. Keep the included [licence](LICENSE.txt) with redistributed copies so downstream users can see their permissions and limitations. The assets are supplied as-is.

## Optional paid kit

PagePatch also sells a separate **[$19 Hero Kit on Ko-fi](https://ko-fi.com/s/515c00b20b)**: three HTML/CSS layouts, a copy worksheet, and an implementation checklist. The free example is part of that promotion. Buying the kit is optional and does not change the free sample’s reuse permissions. The paid kit does not include custom writing, installation, or a review of your website.

## Feedback

If something in the example is confusing or broken, open an issue with the filename and what happened. Do not include private client details or credentials. There is no promised support response time.
