# HTML Documents
* All HTML documents must start with a document type declaration: `<!DOCTYPE html>`
* The HTML document itself begins with `<html>` and ends with `</html>`.
* The visible part of the HTML document is between `<body>` and `</body>`.
```html
<!DOCTYPE html>
<html>
<body>

<h1>My First Heading</h1>
<p>My first paragraph.</p>

</body>
</html>
```

# HTML Headings
HTML headings are defined with the `<h1>` to `<h6>` tags.
`<h1>` defines the most important heading. `<h6>` defines the least important heading: 
```html
<h1>This is heading 1</h1>
<h2>This is heading 2</h2>
<h3>This is heading 3</h3>
```

# HTML Paragraphs
HTML paragraphs are defined with the `<p>` tag:
```html
<p>This is a paragraph.</p>
<p>This is another paragraph.</p>
```

# HTML Links
HTML links are defined with the `<a>` tag:
```html
<a href="https://www.google.com">Here is google</a>
<p>
  Here is <a herf="https://www.youtube.com">you tube</a>
</p>
```

# HTML Images
HTML images are defined with the `<img>` tag.

The source file (`src`), alternative text (`alt`), `width`, and `height` are provided as attributes:
```html
<img src="kitty.jpg" alt="Kitty" width="400" height="400">
```

# HTML Buttons
HTML buttons are defined with the `<button>` tag:
```html
<button>Click me</button>
```

# HTML Lists

HTML lists are defined with the `<ul>` (unordered/bullet list) or the `<ol>`(ordered/numbered list) tag, followed by `<li>` tags (list items):

```html
<h2>An Unordered HTML List</h2>

<ul>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul>  

<h2>An Ordered HTML List</h2>

<ol>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol> 
```