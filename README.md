# GitHub Pages experiment: Latin Prefixed Verbs

This is my first time working with GitHub Pages - experimenting to see how its rendering looks (for desktop and mobile) using a static single-page website, an article on Latin prefixed verbs.

The article is written in Markdown. At first I produced the corresponding HTML locally using Atom's Markdown Preview Plus extension. Resulting site is published [here](https://jnfischer.github.io/github-pages-experiment/prefixedverbs.md.html). The local rendering respects the use of HTML `<small>` tagging to decrease the font size of the text in the entire table.

GitHub Pages can also render HTML from Markdown source itself. Resulting site is published [here](https://jnfischer.github.io/github-pages-experiment/prefixedverbs.html). The renderer doesn't recognize the `<small>` tagging in the Markdown, and the table text is in the same font size as the rest of the article.

A natural next step is to use a static site generator (e.g. Jekyll, Hugo) to render the HTML from the source file using a customizable visual theme.
