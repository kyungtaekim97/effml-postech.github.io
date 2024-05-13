---
type: docs
bookToc: True
weight: 1
---

## Example : Content
This paper propose a compression framework that leverages text information mainly by text-adaptive encoding and training with joint image-text loss. By doing so, they avoid decoding based on text-guided generative models---known for high generative diversity---and effectively utilize the semantic information of text at a global level. 

{{< figure src="./overall_architecture.png" alt="." width="600" height="600" >}}

## Example : Using KaTeX for math equation

KaTeX shortcode let you render math typesetting in markdown document. See [KaTeX](https://katex.org/)

Here is some inline example: {{< katex >}}\pi(x){{< /katex >}}, rendered in the same line. And below is `display` example, having `display: block`
{{< katex display=true >}}
f(x) = \int_{-\infty}^\infty\hat f(\xi)\,e^{2 \pi i \xi x}\,d\xi
{{< /katex >}}
Text continues here.