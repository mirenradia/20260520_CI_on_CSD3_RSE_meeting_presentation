# How to set up CI on CSD3

This repository contains the code to generate the slides for a presentation
about how to set up CI that runs on CSD3 delivered by Miren Radia at a Cambridge
Research Computing Services RSE team meeting on Wednesday 20 May 2026.

## Quarto

These slides are written in [Quarto](https://quarto.org/) markdown in the
[Reveal.js](https://quarto.org/docs/presentations/revealjs/) format.

### Build

To generate the slides, [install Quarto](https://quarto.org/docs/get-started/)
and then execute

```
quarto render slides.qmd
```

It should generate a `slides.html` file which you can open with a web browser.

### GitHub Pages

I will publish the slides to the GitHub pages site associated to this
repository.

## License

The source code (including SVG images) in this repository is licensed under the
[MIT License](./LICENSE). The content of the presentation including text and
slide design is licensed under [CC-BY-4.0][cc-by].

[![CC BY 4.0][cc-by-shield]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg
