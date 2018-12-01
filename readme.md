

This is a collection of literature, resources, opinions and examples that I've mentioned in my seminar at IRD. If you want to send me ideas or comments, feel free [to open an issue](https://help.github.com/articles/creating-an-issue/), send me a [pull request](https://help.github.com/articles/creating-a-pull-request/) or contact me privately

## Bibliography on panicle branching

A very essential bibliography on the work of the EDI team on panicle branching.

- [Gene expression profiling of reproductive meristem types in early rice inflorescences by laser microdissection](https://onlinelibrary.wiley.com/doi/full/10.1111/tpj.13147)
- [Differences in meristem size and expression of branching genes are associated with variation in panicle phenotype in wild and domesticated African rice](https://evodevojournal.biomedcentral.com/articles/10.1186/s13227-017-0065-y)
- [P-TRAP: a Panicle Trait Phenotyping tool](https://bmcplantbiol.biomedcentral.com/articles/10.1186/1471-2229-13-122)


## Tools for the main plot

I produced the main plot completely in R, with [DESeq2](https://bioconductor.org/packages/release/bioc/vignettes/DESeq2/inst/doc/DESeq2.html) to normalize and scale count data, [ggplot2](https://ggplot2.tidyverse.org/index.html) to produce each single component of the plot and [gtable](https://cran.r-project.org/web/packages/gridExtra/vignettes/gtable.html) to combine the different plots maintaining the x axis.


## An example of enabling and encouraging culture in R

1. [ggplot2](https://ggplot2.tidyverse.org/index.html) is openly avalilable.

2. If its functions don't satisfy your need, if you need to produce a more complex plot, [you can learn how to extend it](https://ggplot2.tidyverse.org/articles/extending-ggplot2.html).

3. If you want to make available your extension, you can [publish it as a package](http://r-pkgs.had.co.nz).

4. Once you have made the package, you can [publish its documentation online with pkgdown](https://pkgdown.r-lib.org/), to let everbody know that: you have written a package, why, how other people can use it and what kind of problems they can solve it.

5. If you don't know [how to write documentation](http://r-pkgs.had.co.nz/vignettes.html), they provide technical advice. But also (under the section "Advices for writing communication") they give great practical hints about how to write and communicate effectively, linking to a great blog and an incredibly interesting book.

## Bookdown and books on git.

On [Bookdown](https://bookdown.org/) you can find many open access book (including a book on how to write a book with bookdown). If you click on the github symbol next to most books, you can see how those books are written collaboratively on Git/Github.

## Critical Digital Pedagogy

If you are looking for a discussion of the ethics, approaches and possibilities of digital learning, [An Urgency of Teachers - The work oif critical digital pedagogy](https://criticaldigitalpedagogy.pressbooks.com/) is a great book to start from.

## Writing reviews on Git/Github

[A review on Deep learning in medicine and biology](https://github.com/greenelab/deep-review) written openly on Github[^1].

[^1]: Thanks to Anna Stavrinides for the suggestion.

## Presentation tools

My slides were made with [reveal.js](https://revealjs.com/#/), with its [R markdown format](https://bookdown.org/yihui/rmarkdown/revealjs.html)
