# font-family: The system font stack
```CSS
@font-face {
  font-family: "my-cool-font";
  src: url(../fonts/the-font-file.woff);
}

:root {
    --system-ui: system-ui, "Segoe UI", Roboto, Oxygen-Sans, Ubuntu, Cantarell, Helvetica, Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol";
}
  
.element {
    font-family: "my-cool-font", var(--system-ui);
}
```

If you want to use a font that will not be available on the user’s device, you can import the font from:
- an online font library (like google fonts) or
- an asset on your site (recommended)
Both methods will import the font and make it accessible in your CSS font-family property.
Keep in mind that it’s important to add a fallback font.

more about fonts [here](https://www.theodinproject.com/lessons/intermediate-html-and-css-more-text-styles#ellipsis)