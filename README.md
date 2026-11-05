# Perp.ag docs

Source for https://docs.perp.ag, built and hosted by Mintlify.

- **Guide**: what Perp.ag is, its features and how to use them, with screenshots from the app.
- **API**: the Perp.ag Data API (access by key, on request).
- **API Reference**: generated from `api-reference/openapi.json`.

The source of truth is `landing-page/docs` in `getnimbus/perp_ag`; this repo mirrors it.

## Preview locally

```bash
npx mint dev
```

Check before pushing:

```bash
npx mint validate
npx mint broken-links
```
