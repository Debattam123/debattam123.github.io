# Debattam Das — Personal Academic Website

Source for [debattam123.github.io](https://debattam123.github.io).

## Structure

- `index.html` — Home: about, education, positions, contact
- `research.html` — Research interests, academic visits, awards & grants
- `publications.html` — Papers and preprints (arXiv/DOI links)
- `talks.html` — Talks and conferences attended
- `teaching.html` — Teaching assistantships
- `style.css` — Shared stylesheet (edit colors/fonts here once, applies everywhere)
- `cv.pdf` — Downloadable CV
- `images/` — Photos

## One-time setup (important)

The repo must be named exactly **`Debattam123.github.io`** to serve at the root URL.
Go to the repo → Settings → rename `github.io` → `Debattam123.github.io`.
Then the site appears at `https://debattam123.github.io` (may take a few minutes).

## Adding your photo later

Save a portrait photo as `images/IMG_1869 2.jpg.jpg` (roughly 400×500 px) and push.
The home page picks it up automatically — until then it shows a "DD" placeholder.

## Updating content

Each section is plain HTML. To add a publication, copy an existing `<li>` block in
`publications.html` and edit. Same pattern for talks and teaching.
