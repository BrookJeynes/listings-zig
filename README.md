# listings-zig
A Zig language and style specification for the LaTeX-package listings

## Usage
1. Place the `listings-zig.sty` where `latex` can find it
2. Import `listings` and `listings-zig` in your LaTeX document with `\usepackage{listings, listings-zig}`
3. Select the language `Rust` in the `lstlistings` environment, e.g.
  ```latex
  \begin{lstlisting}[language=Zig]
      // code here
  \end{lstlisting}
  ```
