# Teddy Bear's Diary launch site

Static, dependency-free launch and policy site for GitHub Pages or any static host.

## Files

- `index.html`: English product story and policy links
- `ko/index.html`: Korean product story and policy links
- `legal/`: English policy pages
- `ko/legal/`: Korean policy pages
- `styles.css`: responsive styles and local font definitions
- `assets/`: app icon and locally hosted fonts

## Public URLs after hosting

- English landing: `/`
- Korean landing: `/ko/`
- English privacy policy: `/legal/privacy.html`
- Korean privacy policy: `/ko/legal/privacy.html`
- English account deletion: `/legal/delete-account.html`
- Korean account deletion: `/ko/legal/delete-account.html`
- English terms: `/legal/terms.html`
- Korean terms: `/ko/legal/terms.html`
- English data retention: `/legal/retention.html`
- Korean data retention: `/ko/legal/retention.html`

## Preview

Run a local static server from this directory:

```sh
python3 -m http.server 8765
```

Then open `http://127.0.0.1:8765/`.

## Before publishing

- Replace every `July [day], 2026` placeholder with the approved publication and effective dates.
- Add the public Google Play URL after the store listing is available.
- Review the policy text against the released app, Play Data safety answers, and provider contracts.
- Obtain appropriate legal review for the release markets.

## GitHub Pages

This directory can be copied into a dedicated repository and published from the repository root.

The `EN / 한국어` switch links between matching English and Korean pages.
