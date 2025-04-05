# HTML relevant instruction

Don't need to include "image" in alt text, as screen readers will announce it as "image", followed by the alt text.

Dates should be wrapped in `<time>` tag and provide a `datetime="2023-12-21"` property.

Headings must always be in order, you cannot have a `<h4>` before a `<h2>`.

Document should have one main landmark. `<main role="main">`


# CSS relevant instruction

Descendant selectors like `.class-name p` increase specificity, making the styles harder to override. Instead, give elements a class and use that as the selector.

Have some padding on the `<body>` so elements does not touch the edges on small screen. Do not use `rem` to avoid usable area decrease with bigger font sizes.

Prefer unitless numbers for `line-height` values to multiply the element's own font size.

Set `font-size` on `html` if you use `rem` later in CSS.