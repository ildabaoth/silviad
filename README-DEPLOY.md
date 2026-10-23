# Uploading this to github.com/.../starlet-llama-2512ef

The repository holds the **built site** (`index.html`, the pages, CSS, `assets/`
at the root), so these paths can be copied in as they are.

## 1. Add or replace — two files this time

| file | action |
|---|---|
| `assets/illustrations/shiriko-and-shiina.jpg` | **replace** — the plate, now with the faces the save has |
| `plates.html` | replace — new caption and provenance note |

If you never uploaded the previous batch, take `chapter-1-the-storm.html` and
`house.html` from this zip as well, and delete
`assets/illustrations/kekhan-and-longun.jpg`. If you did upload it, only the two
files above have changed.

## 2. Netlify

It redeploys on every commit to `main`, in about thirty seconds. If nothing
happens, open **Deploys** and read the log.

## 3. Do not

- Add `netlify.toml` while the repository is the built site (`publish = "book"`
  points at a folder that does not exist here).
- Put the source in this repository alongside the built pages.

## 4. Check

`…/plates.html` → Plate XI: two men by a fire on black shingle, the older one in
a fish-skin mantle over a hemp coat, the younger in an indigo robe with a bark-
fibre cape, both with the faces of the men in your save.
