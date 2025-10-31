# TeX Templates


## General Information

This repository includes LaTeX templates for

* manuscripts to be submitted to academic journals,
* dissertations,
* bachelor’s/master’s theses and term papers,
* presentation slides,
* conference posters, and
* (academic) curricula vitae/résumés.


## Noteworthy Features

* The templates for long-form texts (dissertations, article manuscripts, theses, term papers) attempt to typeset the body text such that it adheres to a baseline grid.

* Support for context-based typesetting of mathematical formulas: Formulas in a serif-font environment are typeset using the serif font, while formulas in a sansserif-font environment are typeset using the sansserif font.

* All templates use [`biblatex`](https://ctan.org/pkg/biblatex) with [`biber`](https://ctan.org/pkg/biber) as the backend. (For reasons why to use [`biblatex`](https://ctan.org/pkg/biblatex) with [`biber`](https://ctan.org/pkg/biber) instead of [`natbib`](https://ctan.org/pkg/natbib) with [`bibtex`](https://ctan.org/pkg/bibtex), see [this post on StackExchange](https://tex.stackexchange.com/questions/25701/bibtex-vs-biber-and-biblatex-vs-natbib/25702#25702).)


## Updating

I&nbsp;try to keep my TeX installation up-to-date as much as possible. That is, I&nbsp;check for updates to all TeX packages available on [CTAN](https://ctan.org) about once per week.

Hence, whenever I&nbsp;update this repository, the *.tex* files should compile flawlessly with an up-to-date TeX installation. This entails, however, that they may not compile without errors on older TeX installations. This will happen, in particular, if the update of a&nbsp;package that is used in my templates features backward-incompatible changes.

I&nbsp;am unable to ensure backward compatibility with older TeX installations, since this would be extremely time-consuming. If you are using an older TeX installation, you may, of course, go back in time and download these templates based on earlier commits to this repository. (Say, if you use TeX Live 2023, which is the default TeX installation on Ubuntu 24.04&nbsp;LTS, you might try your luck with commits from 2023.)
