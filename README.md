# Docket images

Public images for the docket.bd blog, served through jsDelivr's CDN.

## Add an image

1. Open the `blog` folder on github.com, then **Add file → Upload files**, and commit.
2. Link it in a post (Markdown body) or in the post's cover image field:

```
https://cdn.jsdelivr.net/gh/randomsapiens1/docket-images@main/blog/<file-name>
```

Example in a post body:

```md
![NID correction form, page 1](https://cdn.jsdelivr.net/gh/randomsapiens1/docket-images@main/blog/nid-correction-form.webp)
```

## Rules

- **Never replace or edit a file in place.** jsDelivr caches `@main` files for
  up to 7 days, so a replaced image can keep showing the old picture. Upload
  a new name instead, e.g. `nid-form-v2.webp`.
- Do not delete images that a published post uses.
- Lowercase names with dashes, no spaces: `sim-check-step-1.webp`.
- WebP, about 1600px wide, under 300 KB. Covers: 16:9 (e.g. 1600×900).
- Only images that are fine to be public. This repo is public.
