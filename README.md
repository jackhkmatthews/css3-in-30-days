# CCS3 in 30 Days

Code examples following [Free Code Camp's youtube playlist](https://www.youtube.com/playlist?list=PLWKjhJtqVAbl1AfjiGyYxwpdAPi5v-1OU).

## Learnings

- CSS variable funcitons take an option second argument to be used as a fallback
- unlike fixed elements who's dimensions are relative to the viewport, sticky positioned element's dimensions are relative to their parents e.g. `width: 100%` and `height: 100%` are relative to parent and not viewport.
- `position: sticky` works well with `display: grid`
- the `~` selector lets you toggle styles of any following sibling based on the state of sibling
- overlays are always there but with `pointer-events: none` and `opacity: 0`.
- border shapes can come in very handy. Think in terms of border top, left, etc and then making one or more `transparent`.
- `*` doesn't select sudo elements.
- can achieve a lot of repeating patterns with `background-image`, `background-size` and `background-position`
- clip path is a powerful tool, hover will also only apply over the clip
- `rect()` function has weird syntax
- `currentColor` can be used to match inherited color
- `box-shadow: inset` can be used to interesting effect
- can use `:target` selector to target elements which match the fragment in the URL. e.g. `href="#tab2"` and `#tab2:target`
- can apply multiple `box-shadows` with a comma seperated list
- `@supports` can be useful for browser compatability issues
