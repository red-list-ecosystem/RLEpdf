# RLEpdf

Quarto extension for a template to generate a PDF with (pretty) LaTeX styling for RLE assessments.

Based on: https://github.com/nrennie/PrettyPDF

## Installation and use

To install the Quarto extension, create a directory, and use the template file:

``` bash
quarto use template red-list-ecosystem/RLEpdf
```

To use the extension in an existing project without installing the template file:

``` bash
quarto install extension red-list-ecosystem/RLEpdf
```
Note that you will need to update the output format to `format: RLEpdf-pdf` to enable use of the extension.

## Changing colours and logo

If you want to update this template to use a different colour or logo, open up the `_extensions/red-list-ecosystem/RLEpdf/RLEpdf.tex` file after you have installed the extension.

### Logo

Either replace the `logo_RLE.png` file with a new file of your choosing, or change the file path on line 28 to point to a different logo file. Note that the file path is relative to your .qmd file.

### Colours

Lines 14-16 define three colours used in the template: `light`, `dark`, and `highlight`. Change the hex colours in these lines to update the colours. The `light` colour changes the sidebar and code block background colours. The `dark` colour changes the text. The `highlight` colour changes the link colours.





