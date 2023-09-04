# Math Formulas in Markdown

## Using MathJax

You can write inline math using single dollar signs, like this: $E=mc^2$. Or, you can use double dollar signs for display math:

$$
F(x) = \int_{a}^{x} f(t) \, dt
$$

## Using KaTeX

To use KaTeX for rendering math formulas, include the necessary scripts and use the `math` code block:

```html
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/KaTeX/0.11.1/katex.min.css">
<script defer src="https://cdnjs.cloudflare.com/ajax/libs/KaTeX/0.11.1/katex.min.js"></script>
<script defer src="https://cdnjs.cloudflare.com/ajax/libs/KaTeX/0.11.1/contrib/auto-render.min.js"></script>
```
