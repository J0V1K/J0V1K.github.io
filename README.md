# Javokhir Arifov: personal site

One self-contained page: `index.html`. Open it in a browser to preview; reload after each save.

## Where things live (search for these in index.html)

| To change | Search for |
|---|---|
| Page 1 of the brief | `id="p1"` |
| Words that fly into a graph word | `<span class="kw" data-node="...">` |
| Page 2 preview on the home page | `id="p2peek"` |
| Publications (Table of Authorities) | `id="view-authorities"` |
| Projects (Index + Exhibits A to K) | `id="view-exhibits"` |
| Service (Declaration) | `id="view-record"` |
| Graph boxes, links, keywords | `const works = [` |
| Law / both colors for keywords | `const LAW = [` and `const BOTH = [` |
| Colors and fonts | `:root {` |
| Header names | `<nav aria-label="Site">` |

## Notes
- Each sheet is 28 numbered lines; extra text makes the numbers run past 28.
- Page links: `#brief`, `#interests`, `#publications`, `#projects`, `#service`, plus `#ex-a` to `#ex-k` and `#toa-a` to `#toa-d`.
- The published copy is a separate artifact; send the edited file back to Claude to republish, or host it yourself (e.g. GitHub Pages).
