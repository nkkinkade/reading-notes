# Read: 12 - Components

## EJS Partials
* Partials come in handy when you want to reuse the same HTML across multiple views
* Partials are similar to functions in that they make large websites easier to maintain as you don’t have to go and change a piece of text in every page it appears in
* Use <%- include( PARTIAL_FILE ) %> where the partial file is relative to the template you use it in
* The <%- %> tags allow us to output the unescaped content onto the page (notice the -)