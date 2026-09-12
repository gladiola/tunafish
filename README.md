# tunafish

This repository now includes a 9x12 children's book LaTeX template in `childrens-book.tex`.

## Template notes

- Uses the same primary font setup as `KandRStyle/ut.tex` from `gladiola/bookwork2`
- Lays out each spread as a left-hand story page and a right-hand illustration page
- Includes 12 boilerplate spreads
- Shows a placeholder frame on illustration pages until artwork files are added

## Add artwork

Put artwork files in `figures/` and keep the filenames in `childrens-book.tex` in sync with those files.

Keep `\alignfirststorypage` immediately before the first `\storyspread` block so the opening story page stays on the left-hand side if you add front matter later.

## Build

Compile with XeLaTeX or LuaLaTeX because the template uses system fonts:

From the repository root:

```bash
xelatex childrens-book.tex
lualatex childrens-book.tex
```
