# PyMol

- pymol colors: https://pymolwiki.org/index.php/Color_Values

## Selection
- `select [name], [selection]`
  - e.g. `select chA, chain A`

## Coloring
- https://www.blopig.com/blog/2021/01/making-pretty-pictures-with-pymol/
- `spectrum [mode], [color1] [color2], [selection]`
  - e.g. `spectrum count, deepsalmon br3, chG`

## Generating graphics

```
set ray_trace_mode, 1
set ambient, 1
unset specular
```
