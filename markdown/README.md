# Markdown Source Files

### Organization
This directory should contain the markdown files with all the class materials:
- Any images needed should be placed in the `img` directory here.
- Files should be named: NAMING CONVENTION HERE
- `github-css.css` is included here to ease converting the markdown files to pdf

### Generating PDFs
- Generated pdf files are in `../pdf/`.
- They should be made using the following command:
  - `pandoc MD_SOURCE -f gfm -o PDF_OUTPUT --pdf-engine=weasyprint --css=github-css.css`
- This required `pandoc` and `weasyprint` are installed.
- This conversion process is not ideal. As it stands the markdown->pdf package for the pulsar editor does a better job of converting. It is possible that just improving the css file will help, but not certain.
