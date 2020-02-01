# 1.2.1 - CSS or Counterfeit Stainless Steel

---

_*actually it's Cascading Style Sheets_

---

<img src='./assets/html_js_css.jpg' />

---

- We use CSS to change the look of our content.
- CSS is used to change page layout, colors, fonts, text-sizes, image size, etc…
- You can do almost anything _presentational_ with CSS.
- You are limited only by your knowledge of CSS.
 
 (can also add images using css)
---

## Link CSS to an HTML page

```html
<head>
    <link href="main.css" rel="stylesheet">
</head>
```

The `<link>` tag is used to import the CSS file containing rules applying the styles to the DOM elements.

---

## CSS Selectors

CSS Selectors are used to specify on which elements to apply styling. 

| Type  | Example     | Note  |
| ----- | ----------- | ----- |
| class | `.my-class` | 👍👍  | fastest
| tag   | `body`      |  👍   | fast
| id    | `#bacon`    |  🚫   | eh

remember id is unique, don't use in css (reserve for javascript)


---

### Example (using tags):

`<h1>My Amazing Blog</h1>`

```css
h1 {
    font-size: 32px;
}
```

---

### Example (using classes):

`<h1 class="blog-title">My Amazing Blog</h1>

for css never use caps or spaces. (spaces makes multiple classes)
`
```css
.blog-title {
    font-size: 32px;
}
```

---

### Example (using ids):

`<h1 id="blog-title">My Amazing Blog</h1>
`
```css
#blog-title {
    ...don't do it.
    use a class instead
}
```

---

When styling HTML, we should

- ALWAYS use classes.
- SOMETIMES use HTML tags. (ie p div h3)
- NEVER use ids.
- NEVER EVER use ids. 🙏

---