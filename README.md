# Gemini (SJTU Theme)

Beamer poster theme with SJTU color scheme, modified from [Gemini](https://github.com/anishathalye/gemini) by Anish Athalye.

---


*Also modified from the original README.md:*

Gemini is a modern LaTeX [beamerposter] theme.



## Dependencies

* A TeX installation that includes [LuaTeX]
    * You also need `latexmk` if you want to use the provided `Makefile`
* LaTeX package dependencies including beamerposter (these usually come with
  your TeX installation, but if not, you can get them from [CTAN])
* [Raleway] and [Lato], which are both available under Open Font License

## Usage

1. Copy the files in this repository (or clone the repository)

1. In `poster.tex`, set up your paper size, column layout, and scale the
   content as necessary

1. Make a copy of `beamercolorthemegemini.sty`, update the `\usecolortheme`
   line in `poster.tex`, and theme the poster to your liking (optional, but
   highly recommended)

1. Run `make` to build your poster

## Themes

Gemini currently includes three color themes:

* `sjtu` (default)
* `gemini`

The alternative themes are intended to be inspiration for you to make your own
color theme. You're highly recommended to make your own color theme (it's
really easy!) or use the default Gemini theme.


## License

Copyright (c) Yifeng Gao. Released under the MIT License. See
[LICENSE.md][license] for details.

[beamerposter]: https://github.com/deselaers/latex-beamerposter
[LuaTeX]: http://www.luatex.org/
[CTAN]: https://ctan.org/
[Raleway]: https://www.fontsquirrel.com/fonts/raleway
[Lato]: https://www.fontsquirrel.com/fonts/lato
[license]: LICENSE.md