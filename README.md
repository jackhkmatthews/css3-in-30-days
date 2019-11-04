# CCS3 in 30 Days

Code examples following [Free Code Camp's youtube playlist](https://www.youtube.com/playlist?list=PLWKjhJtqVAbl1AfjiGyYxwpdAPi5v-1OU).

## Learnings

- CSS variable funcitons take an option second argument to be used as a fallback
- unlike fixed elements who's dimensions are relative to the viewport, sticky positioned element's dimensions are relative to their parents e.g. `width: 100%` and `height: 100%` are relative to parent and not viewport.
- `position: sticky` works well with `display: grid`
- the `~` selector lets you toggle styles of any following sibling based on the state of sibling
- overlays are always there but with `pointer-events: none` and `opacity: 0`.
- border shapes can come in very handy. Think in terms of border top, left, etc and then making one or more `transparent`.
