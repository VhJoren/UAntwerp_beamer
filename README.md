# UAntwerp_beamer

This is a LaTeX beamer theme for the University of Antwerp. It is designed to match the official UAntwerp templates for Microsoft PowerPoint, but also adds some additional features.

## Usage:
- Get the files for UAntwerp_beamer from [GitHub](https://github.com/VhJoren/UAntwerp_beamer).
- Place the files (*.sty files and ./logo subfolder) in a directory where LaTeX can find them. For example, you can put all the files in the directory where you want to create your presentation. Alternatively, you can put them in your texmf repository, such that they become accessible in all folders on your system. For user installations on Unix, these files are typically put in `~/texmf/tex/latex/UAntwerp_beamer`. Running `texhash` may be required.
- Have a look at `UAntwerp_beamer_example.tex`. Here you can find the syntax for frequently used features. It also contains some information on the possible options. You can create your own presentation in a separate .tex file `presentation.tex`, finding imspiration in `UAntwerp_beamer_example.tex`.
- Compile your presentation using LuaLaTeX (or alternatively pdflatex, which works fine, but will use a different font than the official template). On a command line, this would be `lualatex presentation.tex`. At least two compilations are necessary to build the correct result.
- Look at your nice presentation in `presentation.pdf`.

Feel free to suggest new features and improvements.

## License

This software is published under the [lppl-1.3c](http://www.latex-project.org/lppl.txt) license.
