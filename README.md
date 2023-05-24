# listings-zig
A Zig language and style specification for the LaTeX-package listings

## Usage
1. place the `listings-zig.sty` where `latex` can find it
2. import `listings` and `listings-zig` in your LaTeX document with `\usepackage{listings, listings-zig}`
3. select the language `Rust` in the `lstlistings` environment, e.g.
  ```latex
  \begin{lstlisting}[language=Zig]
  // your source code
  \end{lstlisting}
  ```
