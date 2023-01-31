# resume

# How to use this
Most important files are `resume.tex` and everything in `content/`. You need pdflatex (installed with most latex distributions)

## Adding Content
I create a new `.tex` file for each item/experience in `content/`. Take a look at the existing structure for ideas

## Drafting up the resume
`resume.tex` is where you piece together the items in `content/` into your resume. Arrange the items to your liking, use mine for reference.

### Tips
- Fit everything into one page
- I generally use different items for different areas of focus (ML, Systems, Computer Vision, etc.,). This is especially useful if you can't fit everything into one page (lucky you)

## Compiling Resume
Compile with `pdflatex resume.tex`