# ucalgary-poster

A LaTeX poster style for the University of Calgary, to use with the
[tikzposter](https://ctan.org/pkg/tikzposter?lang=en) package.

`ucalgary-poster.sty` contains all the code required, and provides a
`UCalgary` theme for tikzposter (which is loaded automatically). 

It also provides a `\footer` command which lets you add a footer at
the bottom of the poster (for sponsor logos, etc.), and a
`\tpsetpostersize` command that adjusts the internal dimensions after
you've changed the poster size with `\geometry`, if the poster sizes
provided by `tikzposter` are not suitable.

`issotl-poster.tex` is an example.
