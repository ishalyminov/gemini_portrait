# Gemini-portrait

This is a portrait version of @anishathalye's <a href="https://github.com/anishathalye/gemini">gemini</a> LaTeX [beamerposter] theme.
The picture below corresponds to heriotwatt color theme - compatibility with the original ones not tested.

<p align="center">
<a href="https://raw.githubusercontent.com/ishalyminov/gemini_portrait/master/assets/gemini-portrait-heriotwatt.pdf">
<img src="https://raw.githubusercontent.com/ishalyminov/gemini_portrait/master/assets/gemini-portrait-heriotwatt-small.png">
</a>
</p>

# Dependencies

* A TeX installation that includes [LuaTeX]
* LaTeX package dependencies including beamerposter (these usually come with
  your TeX installation, but if not, you can get them from [CTAN])
* [Raleway] and [Lato], which are both available under Open Font License

# Usage

1. Copy the files in this repository (or clone the repository)

1. In `poster.tex`, set up your paper size, column layout, and scale the
   content as necessary

1. Make a copy of `beamercolorthemegemini.sty`, update the `\usecolortheme`
   line in `poster.tex`, and theme the poster to your liking (optional, but
   highly recommended)

1. Run `make` to build your poster

# Design goals

* **Minimal**: clean and easy to read, so that the emphasis is on the content
* **Batteries included**: works and looks good out of the box
* **Easy theming**: easy to create and use a new color theme

# Contributing

Contributions to Gemini such as bug reports, new themes, and new poster
components are greatly appreciated! Given the subjective nature of design,
you're encouraged to open an issue or pull request early to get feedback before
investing a lot of time in implementing a new feature.

# License

Copyright (c) 2018 Anish Athalye. Released under the MIT License. See
[LICENSE.md][license] for details.

[beamerposter]: https://github.com/deselaers/latex-beamerposter
[LuaTeX]: http://www.luatex.org/
[CTAN]: https://ctan.org/
[Raleway]: https://www.fontsquirrel.com/fonts/raleway
[Lato]: https://www.fontsquirrel.com/fonts/lato
[license]: LICENSE.md
