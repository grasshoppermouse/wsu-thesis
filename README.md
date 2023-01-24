
# wsu-thesis

<!-- badges: start -->
<!-- badges: end -->

A [Quarto](https://quarto.org) extension for Washington State University MA theses and PhD dissertations based on the MS Word template available [here](https://gradschool.wsu.edu/pdi/submitting-thesis-dissertation/). This extension targets the `docx` output format, although `pdf` and `html` should work too.

## Installing

If you haven't already, [install Quarto](https://quarto.org/docs/get-started/). Then, in a terminal (not the R console), enter:

```bash
quarto use template grasshoppermouse/wsu-thesis
```

This will install the extension and create example `index.qmd` and `chapter.qmd` files that you can use as a starting place for your thesis.

## Using

Edit the `_quarto.yml` file with your information, e.g., name, thesis title, degree, and so forth.

The `index.qmd` file is required, and contains the title page and other front matter that will be filled in with the information in the `_quarto.yml` file. The `chapter` folder contains stub `chapter.qmd` files. Number the chapter files in order, and add the file names to the `_quarto.qmd` file.

## Note

After rendering, the `docx` file must be manually edited to conform to WSU formatting and other requirements.
