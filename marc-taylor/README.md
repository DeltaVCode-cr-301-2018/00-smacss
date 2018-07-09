##### How did you determine which rules should be placed in each new CSS file?

- **base.css**: We put the Google font import, star selector, body and logo h1 here because [the documentation](https://smacss.com/book/type-base "the documentation") said &quot;include setting heading sizes, default link styles, default font styles, and body backgrounds&quot;.
- **layout.css**: We put the nav, article, aside, and footer section selectors here because the [documentation said](https://smacss.com/book/type-layout "documentation said") to put the major components that shape the page layout.
- **module.css**: We put the majority of our code here because [the documentation](https://smacss.com/book/type-module "the documentation") said this includes our minor components such as navigation bars, and widgets (i.e. the recipe check boxes). We added comment blocks on lines 1, 35, 82, 104 and 135 to separate the modules.

---

##### Did you do any refactoring of the existing CSS? If so, briefly explain what you did and why.

- Originally there was an `h2` selector. We refactored it to `main article h2` so that it was more specific to the main content subheadings.
- Originally there was an `input` selector. We refactored it to `.recipe input` so that it would only style the font within the receipe checkbox widget.
- We added `../` in front of `background-image` style rules on lines 40 and 91. We went to the [real Chocolate Pizza page](http://185.56.84.20/chocolate-pizza/ "real Chocolate Pizza page") to get the png image. 
- We refactored the footer hr and image so that they appeared like the original example.
