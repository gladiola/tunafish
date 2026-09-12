# tunafish

This repository now includes a 9x12 children's book LaTeX template in `childrens-book.tex`.

## Template notes

- Uses the same primary font setup as `KandRStyle/ut.tex` from `gladiola/bookwork2`
- Lays out each spread as a left-hand story page and a right-hand illustration page
- Includes 12 boilerplate spreads
- Shows a placeholder frame on illustration pages until artwork files are added

## Add artwork

Put artwork files in `figures/` and keep the filenames in `childrens-book.tex` in sync with those files.

## Build

Compile with XeLaTeX or LuaLaTeX because the template uses system fonts:

From the repository root:

```bash
xelatex childrens-book.tex
lualatex childrens-book.tex
```
