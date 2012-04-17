Example-Session for creating a presentation from scratch using LaTeX Beamer.

The repository contains the most important concepts. The example document
`talk.tex` is extended in chronological order.

Starting from scratch, each revision introduces a new concept and is compilable
via `pdflatex`.

## Usage ##

After cloning the repository, checkout each revision in chronological order,
look at the changed `talk.tex` in your favourite text editor, compile the file
via `pdflatex` and view the result in a PDF-viewer.

For example using these commands:

    $ git checkout master~17  # where 17 is the number of commits
    $ git show                # should display the 'from scratch' rev
    $ git checkout master~16
    $ git show                # and reload in editor
    $ pdflatex talk           # and (automatically) reload in PDF-viewer
    $ git checkout master~15
    $ git show
    $ pdflatex talk
    ...

## Contact ##

Georg Sauthoff <gsauthof@techfak.uni-bielefeld.de>
