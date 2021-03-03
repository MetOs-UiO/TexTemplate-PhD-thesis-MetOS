# TeXthesis
This is a setup for a paper based phd thesis at MetOs at UiO.

Thanks to Inger Helene Karset for sharing and as far as I am aware, it was  Andreas Vogel  who first put it together and it might have been developed by Ada Gjermundsen and  Christine Smith-Johnsen (also previous phd students at metos).


## Usage and compilation of template
This template can be used with overleaf or your favorite LateX editor. Note that overleaf has an integration with GitHub, so it can be synced to GitHub (a premium version of Overleaf is needed for this).

If you wish to compile directly with the terminal locally you must run the following commands in the given order
```shell
$ pdflatex main.tex
$ bibtex main
$ pdflatex main.tex
$ pdflatex main.tex
```

You can also use the bash script called 'make'. Execute it by typing
```shell
./make

```
in your shell. Follow the instructions on screen.

- The script compiles the latex document which can be seperated into a main document and dependend sections located in different files.
- All figures are expected to be located in a directory called figures_src.
- Original graphics in vector formates will be converted into pdf and moved to figures directory.
- Graphics in pdf or bitmap formats will be linked into a directory figures.
- The compiled document will automatically open in okular if installed else evince will be called.
- A short summary taken from the tex log files is shown on screen, counting the occurance of box under and overflows and missing references.
- There is also an option to compress the file for pdf-a usage.

## Contribution
Suggestions for any improvements and pull requests are highly welcomed!
