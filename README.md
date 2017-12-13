# Spanify

This is just a helper for CoreMedia to turn anchor tags into spans.

In CoreMedia put 3 spaces before the text you want to wrap in a span tag. Then select the middle space with your mouse cursor then insert a link (right-click or format menu) then in the title field type the class name you want the span to have. Do the same after the text you want to wrap, highlighting the middle space character and link it with "end" in the title field.

`npm install spanify` it into your project, then `const spanify = require("spanify")`.

And then call `spanify.spanify()` to scan the page for these anchor tags and replace them with spans.
