# REFLECTION.md

One non-obvious CSS decision I made was how I organized the stylesheet.
I chose to organize the CSS from general styles to more specific
sections. I started with the universal selector and the body because
these rules establish the basic behavior and appearance of the whole
page. After that, I organized styles for the main elements and then
moved toward more specific components. I made this decision because I
wanted the stylesheet to be easier to understand, maintain, and modify
while working on the design.

If I had organized the CSS randomly, the result would have been harder
to follow and debug because I would have had to search through unrelated
rules to find the style I wanted to change. I chose a structured order
because it makes the relationship between general and specific styles
more predictable. This was especially useful when we changed the visual
design and introduced the dark blue `#080736` as the main color. With
the CSS organized logically, it was easier to identify which styles
needed to be changed without affecting unrelated sections.
