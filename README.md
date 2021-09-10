# TeXTemplates


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

I&nbsp;try to keep my TeX installation up-to-date as much as possible. This means that I&nbsp;check for updates to all the TeX packages that are available on [CTAN](https://ctan.org) about once per week.

As a&nbsp;consequence, whenever I&nbsp;update this repository, the *.tex*&nbsp;files should compile flawlessly with an up-to-date TeX installation. This means, however, that they may no longer compile without errors on older TeX installations. This will happen, in particular, if the update of a&nbsp;package that is used by my templates features backward-incompatible changes.

I&nbsp;am unable to ensure backward compatibility with older TeX installations because doing so would be extremely time-consuming. If you are using an older TeX installation, you may, of course, try to go back in time and download these templates based on earlier commits to this repository. (Say, if you use TeX Live 2019, which is the default TeX installation on Ubuntu 20.04&nbsp;LTS, you may try your luck with commits from 2019.)
