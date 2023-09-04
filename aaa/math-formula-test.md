# Math Formulas in Markdown

## Using MathJax

You can write inline math using single dollar signs, like this: $E=mc^2$. Or, you can use double dollar signs for display math:

$$
F(x) = \int_{a}^{x} f(t) \, dt
$$

## Using KaTeX

To use KaTeX for rendering math formulas, include the necessary scripts and use the `math` code block:

<!--
<html>
  <head>
    <script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
  </head>
  <body>

  </body>
</html>

-->
