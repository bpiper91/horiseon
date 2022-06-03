# Horiseon Refactor

![screenshot of the Horiseon home page](./assets/images/screenshot.PNG "Horiseon home page")
*Horiseon home page*

## About the Refactor

The client, Horiseon, requested a refactor of their home page and stylesheet to ensure their codebase follows accessibility standards and is optimized for search engines.

## Summary

I found several ways to improve accessibility and SEO, while also tidying up the code. 

The page title was a placeholder, so I updated it with the company name.

None of the images or icons had alt attributes, so I added them. The icons in the benefits section I left null, but I added alt text for the images in the main content section.

I converted most of the divs to semantic HTML elements that will make the file easier to maintain (header, nav, section, article, and footer). Where necessary, I updated the CSS selectors to reflect the change. The header and footer were styled with class selectors, so I removed those classes and styled the element directly.

I detected superfluous classes with duplicate CSS rules in the stylesheet, so I condensed them to a single class where appropriate and updated the appropriate elements in the HTML file with the new class name, content-tile and benefit-tile.

To aid readability, I added comments to indicate the start of each section of the HTML page. I re-organized the stylesheet and added comments to indicate the corresponding section of the HTML file for each CSS rule.

The footer used a second-level heading for information that didn't belong in a heading, so I converted it to a span tag and copied its style.

## Contact

Brett Piper - <bpiper91@gmail.com>

Deployed application URL: <https://bpiper91.github.io/horiseon>

GitHub repo URL: <https://github.com/bpiper91/horiseon>