# Template Quarto Presentation

The purpose of this repo is to create a template for DataLab presentation slides
using [quarto][quarto]. While quarto does not fully implement all of 
PowerPoint or Google Slides functionality, it is getting close and it offers
code evaluation features not found in other software. The main challenge is that
exporting slides to pdf from revealjs format does not capture all the 
information. In particular, background images and text are not included.

Documentation:

- [Revealjs documenation][rjs]
- [Custom title slide][] (required for title slide speaker notes)
- [Custom format][format]
- Add title slide speaker notes using [title-attributes][ta]
- Add title slide speaker notes using [custom template][ct]

[quarto]: https://quarto.org/docs/presentations/
[rjs]: https://quarto.org/docs/presentations/revealjs/
[ts]: https://quarto.org/docs/presentations/revealjs/advanced.html#custom-template
[format]: https://quarto.org/docs/extensions/formats.html 
[ta]: https://github.com/jgm/pandoc/issues/5237#issuecomment-804267358
[ct]: https://github.com/quarto-dev/quarto-cli/discussions/4824