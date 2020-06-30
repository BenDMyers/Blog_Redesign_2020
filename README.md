# Blog Design System Manifesto

## Guiding Principles

1. Accessibility and responsiveness must always be at the forefront.
2. An element's purpose must always be clear.
3. Minimize markup, and optimize for portability.
4. Cohesion, but not shtick.

## Heuristics

* Only links get underlines, _especially_ if blue is in the design system.
* Focus states should be prominent, especially since this is an accessibility blog.
* Color should never be the sole indicator of information.
* Distinguish between `<b>`/`<i>` and `<strong>`/`<em>`.
* Adhere, as best as possible, to [CUBE CSS](https://piccalil.li/blog/cube-css/).
* Typography should be used intentionally. Every change in typography should tell a story.
  * **Brand font:** Should absolutely be used for headings. Can be used sparingly as accents.
  * **Body font:** Normal text. Optimize for legibility, pair with brand font.
  * **Monospace font:** Can appear inline or in a code block. Should contrast from body font, but pair with it.
* Animations, if any, must be sparse and subtle.
* Images must have an option to be big, to account for diagrams and anything that requires fine detail.