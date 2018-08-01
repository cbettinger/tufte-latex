# tufte-lovecraft-latex
*Note*: This is a fork of https://github.com/Tufte-LaTeX/tufte-latex by Kevin Godby, Bil Kleb, and Bill Wood, originally licensed under the Apache License, Version 2.0.

## Quick Start
Try typesetting `sample-handout.tex` with the following sequence of commands:

    pdflatex sample-handout
    bibtex   sample-handout
    pdflatex sample-handout
    pdflatex sample-handout

The result should look like `sample-handout.pdf`.

The sample book `sample-book.tex` can be compiled with the following sequence of commands:

    pdflatex sample-book
    bibtex sample-book
    makeindex sample-book.idx
    pdflatex sample-book
    pdflatex sample-book
    pdflatex sample-book

The result should look like `sample-book.pdf`.

## Troubleshooting
If you encounter errors of the form

    ! LaTeX Error: File `paralist.sty' not found.

you will need to obtain missing packages from [CTAN](http://ctan.org).

For package installation instructions and answers to many other questions, see the [UK TeX FAQ](http://www.tex.ac.uk/faq/) or search the group [`comp.text.tex`](http://groups.google.com/group/comp.text.tex).

The following packages are required:

* chngpage or changepage
* fancyhdr
* fontenc
* geometry
* hyperref
* natbib and bibentry
* optparams
* pagecolor
* paralist
* placeins
* ragged2e
* setspace
* textcase
* textcomp
* titlesec
* titletoc
* xcolor
* xifthen

The following packages are optional and will be automatically used if installed:

* beramono
* helvet
* ifpdf
* ifxetex
* letterspace (in the microtype package)
* mathpazo
* soul

## Bugs/Features/Support
For kudos, feature requests, patches, or support requests that you feel are _particular_ to the original Tufte-LaTeX package, i.e., not a general LaTeX issue, please use the project's issue tracker available at <https://github.com/Tufte-LaTeX/tufte-latex/issues>.

## License
Copyright © 2018 by Christian Bettinger

Permission to use, copy, modify, and/or distribute this software for any purpose with or without fee is hereby granted, provided that the above copyright notice and this permission notice appear in all copies.

THE SOFTWARE IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES WITH REGARD TO THIS SOFTWARE INCLUDING ALL IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR ANY SPECIAL, DIRECT, INDIRECT, OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS, WHETHER IN AN ACTION OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS ACTION, ARISING OUT OF OR IN CONNECTION WITH THE USE OR PERFORMANCE OF THIS SOFTWARE.

## Original License
Copyright 2007–2015 by Kevin Godby, Bil Kleb, and Bill Wood.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
