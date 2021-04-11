# FRONT END GUIDELINE HANDBOOK
Updated April, 2021 - Mike Vo

## HTML
- Use HTML5
- Define character encoding UTF-8 `<meta charset="utf-8">`
- Use Semantics
- Do not use table for layout
- Use `th` tags for table header elements
- Don't mix quotation marks
- Define title
- `figcaption` first or last child of `figure`
- Close tags
- No inline styles
- Place External CSS Files Within the `head` tag
- Place Javascript files at bottom of body
- Do not inline Javascript
- Lowercase tag names
- Use `h1`-`h6` to outline the page content

## CSS
- Use a Reset or Reset with Normalize.css
- No Inline Styles
- Organize the Stylesheet with a Top-down Structure
- Divide your stylesheet into specific sections: i.e. Global Styles
- Use Hex Code instead of Name Color
- Combine Elements
- Use Shorthand
- Use Absolute Positioning Sparingly
- Hyphens Instead of Underscores for CSS classes
- Make Use of Generic Classes - design patterns / modules
- Shorten Selector Chains
- Name something, be it an ID or a class, by the nature of what it is rather than by what it looks like

### Example CSS file structure:
```css
/* Reset */

/* Typography */

/* Layout */

/* Navigation */

/* UI-elements */

/* Forms */

```


## Javascript
- Call things by their name – easy, short and readable variable and function names
- Avoid globals
- Stick to a strict coding style
- Comment as much as needed but not more
- Keep DOM access to a minimum
- Don’t yield to browser whims
- Don’t trust any data
- Add functionality with JavaScript, don’t create too much content
