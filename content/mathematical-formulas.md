# Mathematical Formulas

## Render Frames and pdflatex

Scribus has Render Frames: a tool for rendering and including the output from software that can process text input and produce PDF files.

One of the per-configured tools is pdflatex.

### Formulas inline with text

If you need to have the formulas inline (inside of an existing text paragraph), you need to insert it as an inline item:

- Create the Render Frame as usual.
- Cut the frame.
- Put the cursor at the text position where you want to insert the formula.
- Paste the formula.

If you want to further edit the inline formula,

- you can try to double click on it, while the containing text frame is in edit mode,
- or you need to find it in "Windows > Inline Items" and double click on it.

### PDF output

By default the formulas will be exported as images.

In order to export them as vectors (and have selectable text) you need to check the "Embed PDF & EPS files (Experimental)" option in the PDF export dialog (more information in the _PDF Output_ section.
