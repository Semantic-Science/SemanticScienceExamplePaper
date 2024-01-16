# SemanticScienceExamplePaper

# Contents
* /media contains an image
* article.html contains the unformatted, Pandoc-output HTML from the Markdown file
* article.md contains the source Markdown file
* article.pdf contains the Pandoc-output PDF from the Markdown file
* article_styled.html contains a Pandoc-output HTML with its CSS swapped for the style from [this](https://gist.github.com/killercup/5917178) user

# Steps

1. Write the Markdown file

2. Run the following to get an HTML
```
pandoc article.md -f markdown -t html -s -o article.html --metadata title="Semantic Science: Publication Beyond the PDF - An Example Scientific Article Written in Markdown"
```

3. Run the following to get a PDF
```
pandoc article.md -f markdown -t pdf -s -o article.pdf
```
4. 
