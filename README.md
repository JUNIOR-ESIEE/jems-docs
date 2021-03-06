# Jems-docs

[![Build Status](https://travis-ci.org/JUNIOR-ESIEE/jems-docs.svg?branch=master)](https://travis-ci.org/JUNIOR-ESIEE/jems-docs)

Template de docs types et de trombi réalisé en LaTeX pour [Junior ESIEE](http://junioresiee.com).

Pour **tester le rendu directement** (sans téléchargement) : [voici le projet déployé sur Overleaf](https://www.overleaf.com/read/sznvmtrsrqww).

# Installation
* Linux (Ubuntu/Debian) : ``sudo apt install make texlive-latex-base texlive-luatex texlive-lang-french texlive-latex-extra texlive-fonts-recommended texlive-xetex``

* En ligne : [Overleaf](https://www.overleaf.com/), aucune installation n'est nécessaire, il suffit d'importer l'archive zip.

# Utilisation
* Pour compiler :
`make DOC=` + *le dossier contenant le main à compiler*

Par exemple : `make DOC=trombi` ou `make DOC=technical_report`.

* Pour tout nettoyer et retrouver un dossier propre :
`make clean`

# Dev
Le présent [dépot Git](https://github.com/JUNIOR-ESIEE/jems-docs) suit une architecture [*git-flow*](https://danielkummer.github.io/git-flow-cheatsheet/#getting_started).

# Auteur
Guillaume U - Pour Junior ESIEE - 2017-2018
