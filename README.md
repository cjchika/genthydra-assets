# GentHydra Assets

Public assets for GentHydra — blog post images, marketing/brand imagery, and
anything else referenced by URL from the website, admin, or blog content.

Not a code repo: no build, no dependencies. Files here are meant to be
linked to directly (e.g. a blog post's featured image URL, embedded body
images) via jsDelivr's free CDN mirror of this repo — no setup, no
account/token, updates within minutes of a push:

```
https://cdn.jsdelivr.net/gh/cjchika/genthydra-assets@main/<path-to-file>
```

Example: `GentHydra_Truck.png` →
https://cdn.jsdelivr.net/gh/cjchika/genthydra-assets@main/GentHydra_Truck.png

Pin to a commit SHA instead of `@main` for anything that should never
change once published (jsDelivr caches `@main` for ~7 days, so an
in-place file replacement can take a while to propagate — a new
filename or a SHA-pinned URL is instant instead).
