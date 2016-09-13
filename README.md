# hausarbeit-jura
```
----------------------------------------------------------------------------
hausarbeit-jura -- A LaTeX class for writing “juristische Hausarbeiten” at German 
                   universities.
            
(c) 2012-2016 Martin Sievers
Version:    1.5
Maintainer: Martin Sievers
Email:      martin.sievers@schoenerpublizieren.de
License:    Released under the LaTeX Project Public License v1.3c or later
See:        http://www.latex-project.org/lppl.txt
----------------------------------------------------------------------------

This is the current version of the class “hausarbeit-jura” for 
writing “juristische Hausarbeiten” at German universities. It 
was originally developed for a workshop at Trier University.

The idea is to make the usage of LaTeX easier as only a few macros and 
environments are needed.

The documentation is in German only.

Stable versions are always uploaded to CTAN. You'll find the most recent developer version on GitHub.
```

https://github.com/sieversMartin/hausarbeit-jura


## Changelog

### 1.4 to 1.5

* Added ``\sectionbefore`` and ``\sectionafter`` to ``\section`` as well
* Added macros ``\setspacebeforechapter``, ``\setspaceafterchapter``, ``\setspacebeforesection`` and ``\setspaceaftersection``
* Added option ``noautomatter`` to deactivate automatic usage of ``\frontmatter`` and ``\mainmatter``

### 1.3 to 1.4

* Added macros to change paper size used in frontmatter and mainmatter (suggested by Adi Sander)
* Added definition for ``\subsubsection``
* Modifed ``microtype`` options

### 1.2 to 1.3

* Fixed a bug (missing ``\fi``)
* Added option ``headlinetitlepageleft``
* Added package ``ellipsis``

### 1.1 to 1.2

* added option ``headline`` (thanks to Tobias Hirning) to add information to the header
* TeX Gyre Fonts are now the standard fonts; added new option ``oldfonts`` for compatibility
* added support for XeLaTeX and LuaLaTeX
* rearranged package (not only) for GitHub
* code cleaning and improvement

### 1.0.1 to 1.1

* added a documentation
* modified demo file

### 1.0 to 1.0.1

* dtx now extracts “README.txt” instead of “README”.
* code cleaning of the dtx file

### 1.0

* First “official” version, still without documentation

