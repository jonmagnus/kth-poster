# KTH-poster [![Build Status](https://github.com/jonmagnus/kth-poster/actions/workflows/ci.yml/badge.svg)](https://github.com/jonmagnus/kth-poster/actions/workflows/ci.yml)

An unofficial poster template for KTH Royal Institute of Technology.
KTH-poster is a fork of [Gemini](https://github.com/anishathalye/gemini).

## Dependencies

* A TeX installation that includes [LuaTeX]
    * You also need `latexmk` if you want to use the provided `Makefile`
* LaTeX package dependencies including beamerposter (these usually come with
  your TeX installation, but if not, you can get them from [CTAN])
* Fonts [Figtree] and [Georgia].

## Usage

1. Copy the files in this repository (or clone the repository)

1. Install Figtree form e.g. Google Fonts, and Georgia (if not already installed).

1. In `poster.tex`, set up your paper size, column layout, and scale the
   content as necessary

1. Run `latexmk` to build your poster


## Themes

Gemini currently includes the following color themes:

* `kth` (default)
* `gemini`
* `mit`
* `umich`
* `labsix`

## License

Copyright (c) Anish Athalye. Released under the MIT License. See
[LICENSE.md][license] for details.

[beamerposter]: https://github.com/deselaers/latex-beamerposter
[Auriga]: https://github.com/anishathalye/auriga
[LuaTeX]: http://www.luatex.org/
[CTAN]: https://ctan.org/
[Raleway]: https://www.fontsquirrel.com/fonts/raleway
[Lato]: https://www.fontsquirrel.com/fonts/lato
[license]: LICENSE.md
[FAQ]: https://github.com/anishathalye/gemini/wiki/FAQ
