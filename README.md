# XRaD Website

Website of the Section of Experimental Radiology (XRaD), Ulm University Medical Center, built with [Quarto](https://quarto.org).

## Structure

| File | Page |
| --- | --- |
| `index.qmd` | Home |
| `research.qmd` | Research topics |
| `publications.qmd` | Publication list |
| `people.qmd` | Team |
| `open_positions.qmd` | Open positions |
| `contact.qmd` | Contact |
| `styles.css` | Site styles |
| `files/images/` | Logos and page images |
| `files/profiles/` | Team photos |

## Build

```sh
quarto preview   # live preview
quarto render    # build into docs/
```

The rendered site is written to `docs/` for GitHub Pages.

Based on the [Quarto Academic Website Template](https://github.com/drganghe/quarto-academic-website-template) by Dr. Gang He.
