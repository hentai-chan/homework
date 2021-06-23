# English Essay Template

## About

Very simplistic LaTeX template for writing math homework assignments.

## Compile

This example uses Advanced Systems' [Math Macros](https://github.com/Advanced-Systems/mathmacros); while this package is in development, it
is recommended to pull it in as a git submodule:

```cli
git submodule update --init --recursive
```

Both TeX Live and MikTeX come with `latexmk`, though since this is a
perl script you need to have perl installed on your system to run
this command. Alternatively, use the `pdflatex` command.

```cli
latexmk document.tex -outdir=build -pdf
```

## Clear Cache

```cli
latexmk -C -outdir=build
```
