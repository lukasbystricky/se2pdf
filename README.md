# se2pdf

A script to convert epubs from [Standard Ebooks](https://standardebooks.org) to PDFs. It can be called by providing the identifier of the epub, for example

`python3 se2pdf.py sarah-louisa-forten-purvis_poetry`

## Dependencies
- [Weasyprint](https://weasyprint.org)
- [cssutils](https://pypi.org/project/cssutils/)
- [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)

## To do
- Clean up code: add command line options, replace regex with better use of BeautifulSoup
- Automatic scaling of text on back cover
- Replace "see here" notes with page reference
- Add option to convert endnotes to footnotes
- Probably lots of other things
