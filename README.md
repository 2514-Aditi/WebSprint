
# Websprint: HTML & CSS Reference

## HTML Basics

### 1. HTML Document Structure

```html
<!DOCTYPE html>
<html>
  <head>
    <title>My Web Page</title>
  </head>
  <body>
    <h1>Welcome to My Page</h1>
  </body>
</html>
```

### 2. Head Tag

```html
<head>
  <title>Page Title</title>
  <link rel="stylesheet" href="styles.css">
</head>
```

### 3. Body Tag

```html
<body>
  <h1>Main Content</h1>
  <p>This is a paragraph in the body.</p>
</body>
```

### 4. Paragraph Tag

```html
<p>This is a paragraph of text.</p>
```

### 5. Headings

```html
<h1>Main Heading</h1>
<h2>Subheading</h2>
<h3>Section Heading</h3>
<h4>Subsection</h4>
<h5>Note</h5>
<h6>Minor Note</h6>
```

### 6. Hyperlink Tag

```html
<a href="https://example.com">Visit Example</a>
```

### 7. Image Tag

```html
<img src="image.jpg" alt="A description of the image" width="300">
```

### 8. Unordered List

```html
<ul>
  <li>Item 1</li>
  <li>Item 2</li>
</ul>
```

### 9. Ordered List

```html
<ol>
  <li>First</li>
  <li>Second</li>
</ol>
```

### 10. HTML Table Example

```html
<table border="1">
  <tr>
    <th>Item</th>
    <th>Description</th>
    <th>Price</th>
  </tr>
  <tr>
    <td>Burger</td>
    <td>Cheesy delight</td>
    <td>$5</td>
  </tr>
</table>
```

### 11. Merging Table Cells

```html
<table border="1">
  <tr>
    <th colspan="2">Merged Header</th>
  </tr>
  <tr>
    <td>Cell 1</td>
    <td>Cell 2</td>
  </tr>
</table>
```

### 12. Div Tag

```html
<div>
  <h2>Section Title</h2>
  <p>This is a content block.</p>
</div>
```

### 13. Form, Input and Label

```html
<form action="/submit" method="post">
  <label for="name">Name:</label>
  <input type="text" id="name" name="name">
  <br>
  <label for="email">Email:</label>
  <input type="email" id="email" name="email">
  <br>
  <input type="submit" value="Submit">
</form>
```

## CSS Basics

### 1. Introduction to CSS

```css
body {
  font-family: Arial, sans-serif;
}
```

### 2. CSS Selectors

```css
h1 {
  color: darkblue;
}

#main {
  padding: 20px;
}

```

### 3. Typography

```css
p {
  font-size: 16px;
  font-weight: bold;
  font-style: italic;
}
```

### 4. Colors and Backgrounds

```css
body {
  background-color: #f4f4f4;
  color: #333;
}
```

### 5. Inline, Internal, and External CSS

#### Inline

```html
<p style="color: red;">This is red text.</p>
```

#### Internal

```html
<head>
  <style>
    body {
      background-color: lightblue;
    }
  </style>
</head>
```

#### External

```html
<link rel="stylesheet" href="style.css">
```

---
