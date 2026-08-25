---
layout: post
title: "Post title"
date: 2026-01-01
description: "One line summary, used for the <meta description> and link previews."
---

First paragraph.

## A section

More writing.

**Maths must use double dollars — `$$x_t$$` — for inline as well as display.**
Kramdown (what GitHub Pages runs) does not recognise single `$...$` as maths: it
leaves the dollars as literal text and turns the underscores inside into italics.
An equation on its own line renders as a centred display equation:

$$L = \| a - b \|^2$$

Figures live in `figures/` and are written as raw HTML so they can carry a caption:

<figure>
  <img src="figures/example.png" alt="Describe the figure" />
  <figcaption>Caption. From Author et al. [1].</figcaption>
</figure>

## References

<ol class="refs">
  <li>A. Author et al., <em>Title</em> (2026). <a href="https://example.com">example.com</a></li>
</ol>
