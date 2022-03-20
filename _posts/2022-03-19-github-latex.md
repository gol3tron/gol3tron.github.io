---
layout: post
title: "Adding basic $$\LaTeX$$ to a post in github pages"
date: 2022-03-19
tags: code help
---

Wondering if github pages/Jekyll supports $$\LaTeX$$? It does!

#### What is $$\LaTeX$$?

$$\LaTeX$$ is an elegant language for typesetting and is particularly useful for mathematical expressions. It has a very straightforward and easy to learn process that will have you writing the most complex equations on a computer with ease in no time! 

#### How do I do it in Jekyll/github pages?

Pretty simple, it turns out! You need to do the following...

1. Specify "kramdown" in your `_config.yml` file...

```markdown
markdown: kramdown
```
2. Add the following script to the `_includes/head.html` file in your website repo directory before the `</head>` tag

```html
<script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
```

3. Start writing! You can create an inline equation with dollar-sign tags, i.e. `$$x+4$$` will typeset as $$x+4$$. Similarly, centered individual equations can be typeset between raw liquid tags as follows:

```
{% raw %}
\begin{equation}
x = \frac{-b^{2} \pm \sqrt{b^{2} - 4ac}{2a}
\end{equation}
{% endraw %}
```

will typeset as...

{% raw %}
\begin{equation}
x = \frac{-b^{2} \pm \sqrt{b^{2} - 4ac}{2a}
\end{equation}
{% endraw %}

And there you go! Happy typesetting!
