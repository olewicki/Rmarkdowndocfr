# Document pour apprendre à utiliser le package "R markdown"

Le document `ex_Rmarkdown.md` est un exemple assez complet pour utiliser:

  1. la syntaxe Pandoc Markdown;
  2. les fonctionnalités du packages `rmarkdown`.

Pour installer le package&nbsp;:

```R
install.packages("rmarkdown")
```

Pour générer le fichier document pdf donné&nbsp;:

```R
rmarkdown:: render("ex_Rmarkdown.rmd", "pdf_document")
```

où *path* est le chemin vers le document. De même pour obtenir le document en html, mardown, pdf et word&nbsp;:


```R
rmarkdown:: render("ex_Rmarkdown.rmd", "all")  
```

# Remerciements.

Merci à Nicolas Casajus pour avoir corrigé des coquilles dans le document!

# License

Le document produit sous la license [*Creative Commons BY-NC-SA*](https://creativecommons.org/licenses/by-nc-sa/2.0/)
