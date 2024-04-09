<!DOCTYPE html>
<html>
<head>
    <title>LaTeX Equation Display</title>
    <!-- Load MathJax -->
    <script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
    <script>
        window.MathJax = {
            tex: {
                inlineMath: [['$', '$'], ['\\(', '\\)']]
            },
            svg: {
                fontCache: 'global'
            }
        };
    </script>
    <script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-svg.js"></script>
</head>
<body>

<h2>LaTeX Equation in HTML</h2>
<p>Here's an inline equation: $E=mc^2$</p>

</body>
</html>
