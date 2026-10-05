# Banner source

`research.svg` is the editable banner, with Times New Roman lettering.
The published SVG uses vector outlines; the PNG is exported at twice the source
resolution (2560 × 720).

The [figure renderer](https://github.com/JasonGao1010/JasonGao1010.github.io/blob/main/scripts/render_figures.py)
exports both formats using Times New Roman and Chromium. From this repository:

```sh
python /path/to/render_figures.py assets/source/research.svg assets/research.svg --png assets/research.png
```
