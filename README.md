# listings-hcl
$\LaTeX$ listings package extension for [HCL](https://www.terraform.io/language).

## Usage
1. place the `listings-hcl.sty` where $\LaTeX$ can find it
1. import `listings` and `listings-hcl` in your $\LaTeX$ document with `\usepackage{listings,listings-hcl}`
1. select the language `HCL` in the `lstlistings` environment, e.g.
   ```tex
   \begin{lstlisting}[language=HCL]
   # your source code
   \end{lstlisting}
   ```
1. optional: select one of the styles `light` or `dark`, e.g.
   ```tex
   \begin{lstlisting}[language=HCL,style=light]
   # your source code
   \end{lstlisting}
   ```

## Documentation
Currently there is only the style-file itself and the example document `example.tex` for documentation.

## Visualization
See [example.pdf](example.pdf)
