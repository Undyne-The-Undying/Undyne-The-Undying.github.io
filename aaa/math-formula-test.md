# Math Formulas in Markdown

## Using MathJax

You can write inline math using single dollar signs, like this: $E=mc^2$. Or, you can use double dollar signs for display math:

$$
F(x) = \int_{a}^{x} f(t) \, dt
$$

## Using KaTeX

To use KaTeX for rendering math formulas, include the necessary scripts and use the `math` code block:


<!--
<head>
    <script type="text/javascript" async
        src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.7/MathJax.js?config=TeX-MML-AM_CHTML">
    </script>
    <script type="text/x-mathjax-config">
        MathJax.Hub.Config({
            tex2jax: {
                inlineMath: [['$', '$'], ['\\(', '\\)']],
                displayMath: [['$$', '$$'], ['\\[', '\\]']],
                processEscapes: true
            }
        });
    </script>
</head>
-->
