# tunafish

This repository now includes a 9x12 children's book LaTeX template in `childrens-book.tex`.

## Template notes

- Uses the same primary font setup as `KandRStyle/ut.tex` from `gladiola/bookwork2`
- Lays out each spread as a left-hand story page and a right-hand illustration page
- Includes 12 boilerplate spreads
- Includes 12 placeholder illustration files that can be replaced with final artwork

## Add artwork

Replace the placeholder files in `figures/` with your final artwork, or update the filenames in `childrens-book.tex` if you want to use different names.

## Build

Compile with XeLaTeX or LuaLaTeX because the template uses system fonts:

From the repository root:

```bash
xelatex childrens-book.tex
lualatex childrens-book.tex
```
