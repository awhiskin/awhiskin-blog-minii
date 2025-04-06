---
title: "Math Typesetting"
date: 2024-04-01
categories: ["Fuckers"]
tags: ["academic", "math", "katex"]
math: true
---

Mathematical notation can be enabled in Hugo using various JavaScript libraries, such as KaTeX or MathJax. Once set up, you can write LaTeX-style math equations directly in your Markdown content.

## Example Equations

When $a \ne 0$, there are two solutions to $ax^2 + bx + c = 0$ and they are
$$x = {-b \pm \sqrt{b^2-4ac} \over 2a}.$$

Inline math: $e^{i\pi} + 1 = 0$

Block math:
$$
\int_{-\infty}^{\infty} e^{-x^2} dx = \sqrt{\pi}
$$

Here's Maxwell's Equations:

$$
\begin{aligned}
\nabla \times \vec{\mathbf{B}} -\, \frac1c\, \frac{\partial\vec{\mathbf{E}}}{\partial t} & = \frac{4\pi}{c}\vec{\mathbf{j}} \\
\nabla \cdot \vec{\mathbf{E}} & = 4 \pi \rho \\
\nabla \times \vec{\mathbf{E}}\, +\, \frac1c\, \frac{\partial\vec{\mathbf{B}}}{\partial t} & = \vec{\mathbf{0}} \\
\nabla \cdot \vec{\mathbf{B}} & = 0
\end{aligned}
$$

## Setting Up Math Support

To enable math support in your Hugo site, you need to:

1. Add a JavaScript library like KaTeX or MathJax to your site
2. Configure your content to use math rendering
3. Write equations using LaTeX syntax

Here's an example configuration for using KaTeX with Hugo:

```html
<!-- In your header template -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/katex@0.16.4/dist/katex.min.css">
<script defer src="https://cdn.jsdelivr.net/npm/katex@0.16.4/dist/katex.min.js"></script>
<script defer src="https://cdn.jsdelivr.net/npm/katex@0.16.4/dist/contrib/auto-render.min.js" onload="renderMathInElement(document.body);"></script>
```

This is just a basic example. For a fully functional math typesetting setup, you may need additional configuration.
