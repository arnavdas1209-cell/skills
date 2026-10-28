---
name: research-disseminator
description: Creates post-publication dissemination materials for a published paper that stay faithful to the science while being accessible. It produces a plain-language summary, a graphical-abstract concept, and social-media content tailored per platform, with image-based content for a blog, a WeChat channel, and Xiaohongshu, and text-plus-image content for LinkedIn, X, and Bluesky, applying each platform's length limit, language, and tone. It never overclaims or distorts the findings, invents numbers, or implies conclusions the paper does not support, and it links back to the paper. Use whenever the user wants to promote, share, or communicate a published paper, needs a plain-language or lay summary, a graphical abstract, a social-media thread, or platform-specific posts about their research. Chinese-platform content (WeChat, Xiaohongshu) is written in Chinese; the rest defaults to English.
---

# Research Disseminator

Turn a published paper into accessible dissemination materials that reach non-specialists and social audiences, tailored to each platform.

## The one rule that cannot be broken

**Faithful, no loss.** Make the science accessible without distorting or overclaiming it. Simplify the language, never the facts: no invented numbers, no hype beyond what the paper supports, no causal claim the data do not justify, and represent limitations and uncertainty honestly. "Accessible" never means "exaggerated". Every piece links back to the paper (DOI or URL) so readers can verify.

## Inputs

- **The published paper** (or its abstract, key findings, and DOI/link). Draw the summary and posts from what the paper actually says.
- **Target platforms** (any of: blog, WeChat channel, Xiaohongshu, LinkedIn, X, Bluesky).
- **Author and credit details** (handles to tag, co-authors, institution, funder) and any figure usable for a graphical abstract.

## Materials

1. **Plain-language summary:** what was done, what was found, and why it matters, in jargon-free language a general reader understands, faithful to the paper.
2. **Highlights (bullet points):** 3 to 5 concise, faithful bullet points capturing the key advances of the research. These anchor the message and are carried into every platform's material.
3. **Graphical-abstract concept:** a simple visual that conveys the main finding at a glance. Describe the layout, or generate a clean schematic with the visualization capability; keep it accurate and use no copyrighted, branded, or licensed imagery.
4. **Platform posts:** the copy (and image direction) for each requested platform, per `references/platform-specs.md`.

## Platform tailoring

Two families (details, limits, language, and tone in `references/platform-specs.md`):

- **Image-based** (lead with visuals): blog, WeChat channel, Xiaohongshu; provide the image concept(s) plus the accompanying copy.
- **Text plus image** (lead with text): LinkedIn, X, Bluesky, and also WeChat channel (Chinese, under 1500 words) and Xiaohongshu (Chinese, under 450 words); provide the post(s) plus one supporting image direction.

WeChat channel and Xiaohongshu can therefore be delivered either way; pick the family the user asks for. Apply each platform's length limit, language, and register, and carry the bullet-point highlights into every platform's material. Chinese platforms (WeChat channel, Xiaohongshu) are written in Chinese; blog, LinkedIn, X, and Bluesky default to English (adjust to the author's audience if they ask).

## Workflow

1. Extract the core message from the paper: the one main finding, why it matters, and the honest scope (what it does and does not show).
2. Write the plain-language summary first; it is the faithful base every other piece draws from. Then distill 3 to 5 bullet-point highlights from it.
3. Draft the graphical-abstract concept from the main finding.
4. Generate each requested platform's material from `references/platform-specs.md`, respecting its length limit, language, and tone, carrying the highlights into every one, and adapting the message rather than pasting the same text everywhere.
5. Add the paper link and appropriate credits/tags to each piece.
6. Do a faithfulness pass: check nothing overclaims, no number is invented, limitations are not erased, and every piece is traceable to the paper.

## Output

The requested set: plain-language summary, bullet-point highlights, graphical-abstract concept, and per-platform posts, each labeled with its platform and ready to copy, with the paper link included. Flag anything that needs the author (a handle to tag, a figure file, a funder to credit) with `[[NEEDS AUTHOR INPUT: ...]]`.

## Cautions

Accessibility must not cost accuracy; when a simplification would mislead, keep the nuance. Do not fabricate engagement bait or claims of significance the paper does not make. Respect platform norms and limits, and do not use copyrighted images.
