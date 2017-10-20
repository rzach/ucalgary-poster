# ucalgary-poster

A LaTeX poster style for the University of Calgary, to use with the
[tikzposter](https://ctan.org/pkg/tikzposter?lang=en) document class.

`ucalgary-poster.sty` contains all the code required, and provides a
`UCalgary` theme for `tikzposter` (which is loaded automatically). 

It also provides a `\footer` command which lets you add a footer at
the bottom of the poster (for sponsor logos, etc.), and a
`\tpsetpostersize` command that adjusts the internal dimensions after
you've changed the poster size with `\geometry`, if the poster sizes
provided by `tikzposter` are not suitable.

`issotl-poster.tex` is an example. The University of calgary logo in
the header is provided as `uc-vert-cmyk-white-text.pdf`. You'll need
to get your sponsor logos from somewhere else. Try to get a PDF, or EPS
and convert to PDF (e.g., run through
[`epstopdf`](https://ctan.org/pkg/epstopdf?lang=en)). You can request
department lockups and wordmarks from [UCalgary
Brand](https://www.ucalgary.ca/brand/logos/request). NSERC logo
[here](http://www.nserc-crsng.gc.ca/NSERC-CRSNG/VisualIdentity-IdentiteVisuelle_eng.asp)
and SSHRC
[here](http://www.sshrc-crsh.gc.ca/about-au_sujet/sshrc-logo-crsh/index-eng.aspx).
