# tunafish

This repository now includes a 9x12 children's book LaTeX template in `childrens-book.tex`.

## Template notes

- Uses the same primary font setup as `KandRStyle/ut.tex` from `gladiola/bookwork2`
- Lays out each spread as a left-hand story page and a right-hand illustration page
- Includes 12 boilerplate spreads
- Draws a placeholder illustration panel on each right-hand page until you add real artwork paths

## Add artwork

Put artwork files in `figures/`, then replace the empty third argument in each `\storyspread{...}{...}{}` call with the full path to the matching image, such as `figures/illustration-01.png`.

## Build

Compile with XeLaTeX or LuaLaTeX because the template uses system fonts:

From the repository root, choose one engine:

```bash
xelatex childrens-book.tex
lualatex childrens-book.tex
```
