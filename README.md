# Code Refactor Starter Code

Horiseon Optimization

https://parkerrobison.github.io/horiseon-optimization/

Code refactotr Horiseon's website so that it meets accessibility standards and that it is optmized for search engines. Shanges were made in the folllowing documents:

-index.html
-style.css

Documentation

html
-added an id of "search engine optimization" SEO's <article>.
-added alt attributes for the applicable images.
-added an aria label for the hero/jumbotron image
-added semantic HTML for improved readability. (<header>, <article>, <section>, etc.)
-fixed incomplete HTML.

css
-renamed selectors so they would style matching semantic HTML. (eg. div -> nav)
-included font-family in the body selector to reduce redundant attributes.
-increase font-size for better visibility.
-added line-height to increase readability.
-gave articles a class of services to consolidate cs code. (for img, h2, and article)
-Consolidated specific class selectors to .benefits img
-Consolidated specific class selectors to .benefits h3
-Consolidated specific class selectors to .benefit