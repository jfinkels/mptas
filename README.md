Clarification of a proof of completeness in classes of approximable
optimization problems
===================================================================

This work presents a more precise proof of a theorem that provides sufficient
conditions for an optimization problem to be hard for a class of approximable
optimization problems under MPTAS reductions.

This file was last updated on 3 April 2013.

Downloading
-----------

This paper can be found at https://github.com/jfinkels/mptas.

To download the paper using [Git][1], run

    git clone git://github.com/jfinkels/mptas

[1]: http://git-scm.com

A somewhat recent version of this work should be available at
http://cs-people.bu.edu/jeffreyf/files/mptas, but I can't guarantee that that
will always be up to date, since I compile and upload it manually.

Compilation dependencies
------------------------

Besides `pdflatex`, compile-time dependencies include the following LaTeX
packages:

* `amsmath`
* `amssymb`
* `amsthm`
* `complexity`
* `hyperref`
* `thmtools`
* `algorithmicx`

On Ubuntu 11.04, 11.10, 12.04, or 12.10, the necessary system packages which
contain these LaTeX packages are:

* `texlive-base`
* `texlive-latex-base`
* `texlive-latex-extra`
* `texlive-science`

To install them, run

    sudo apt-get install texlive-base texlive-latex-base texlive-latex-extra \
      texlive-science

Compiling
---------

To compile the document, run

    pdflatex mptas
    bibtex mptas
    pdflatex mptas
    pdflatex mptas

The output is `mptas.pdf`, and can be viewed with any PDF reader.

Copyright
---------

Copyright 2013 Jeffrey Finkelstein.

Except where otherwise noted, both the LaTeX markup and the content of the
article are made available under the terms of the Creative Commons
Attribution-ShareAlike 3.0 license,
https://creativecommons.org/licenses/by-sa/3.0/.

Contact
-------

Jeffrey Finkelstein <jeffrey.finkelstein@gmail.com>
