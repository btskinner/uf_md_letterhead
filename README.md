# Markdown version of UF letterhead

This markdown file and template follows the [UF standard for
letterhead](http://identity.ufl.edu/stationery/). 

## To use

Fill out yaml and replace stock text in the body of the `letter.md`
file. Compile using the following command in the terminal:

``` bash
pandoc ./letter.md --read=markdown --write=latex --output=./letter.pdf --pdf-engine=xelatex --template=letter_template.tex
```

