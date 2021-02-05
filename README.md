# TeXthesis
This is a setup for a paper based phd thesis at MetOs at UiO.

Thanks to Inger Helene Karset for sharing and as far as I am aware, it was  Andreas Vogel  who first put it together and it might have been developed by Ada Gjermundsen and  Christine Smith-Johnsen (also previous phd students at metos).


## Usage and compilation of template
This template can be used with overleaf or your favorite LateX editor. Note that overleaf has an integration with GitHub, so it can be synced to GitHub (a premium version of Overleaf is needed for this).

If you wish to compile with the terminal locally you must run the following commands in the given order
```shell
$ pdflatex main.tex
$ bibtex main
$ pdflatex main.tex
$ pdflatex main.tex
```

## Contribution
Suggestions for any improvements and pull requests are highly welcomed!
