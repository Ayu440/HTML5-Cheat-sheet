# HTML5-Cheat-sheet
This is a cheat sheet of HTML5 for quick revision and help.

## HTML5 Cheatsheet

### What is an Element?
An HTML element represents a part of the webpage. It consists of a start tag, content, and an end tag.

```html
<p>This is a paragraph.</p> <!-- Paragraph Element -->
<div>This is a division.</div> <!-- Division Element -->
```

**Example:**

This is a paragraph.

This is a division.

### What is a Tag?
An HTML tag is a keyword enclosed in angle brackets (<>) that defines how the browser should display the content.

```html
<h1>Heading 1</h1> <!-- Opening and Closing Tags -->
<br> <!-- Self-closing Tag -->
```

**Example:**

Heading 1

A line break is represented using a self-closing tag:

This text appears after a line break.

### What is an Attribute?
An attribute provides additional information about an element. It is defined in the opening tag and typically comes in name-value pairs.

```html
<a href="https://example.com" target="_blank">Visit Example</a> <!-- 'href' and 'target' are attributes -->
<img src="image.jpg" alt="Description"> <!-- 'src' and 'alt' are attributes -->
```

**Example:**

Visit Example

The link above uses the href and target attributes.

### Basic HTML5 Structure

```html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="description" content="HTML5 Cheatsheet">
<title>HTML5 Cheatsheet</title>
</head>
<body>
<h1>Hello World</h1>
</body>
</html>
```

### Meta Tags

```html
<meta charset="UTF-8"> <!-- Specifies character encoding -->
<meta name="viewport" content="width=device-width, initial-scale=1.0"> <!-- Makes site responsive -->
<meta name="description" content="HTML5 Cheatsheet"> <!-- Page description -->
<meta name="author" content="Your Name"> <!-- Author of the page -->
<meta http-equiv="X-UA-Compatible" content="IE=edge"> <!-- Browser compatibility -->
<meta name="robots" content="index, follow"> <!-- Search engine indexing -->
```

### Links

```html
<a href="https://example.com">Visit Example</a> <!-- Hyperlink -->
<a href="#section1">Go to Section 1</a> <!-- Internal link -->
<a href="mailto:someone@example.com">Send Email</a> <!-- Email link -->
```

### Headings

```html
<h1>Main Heading</h1>
<h2>Subheading</h2>
<h3>Smaller Heading</h3>
<h4>Subheading 4</h4>
<h5>Subheading 5</h5>
<h6>Subheading 6</h6>
```

### Text Formatting Tags

```html
<b>Bold Text</b>
<i>Italic Text</i>
<strong>Important Text</strong>
<em>Emphasized Text</em>
<mark>Highlighted Text</mark>
<small>Small Text</small>
<del>Deleted Text</del>
<ins>Inserted Text</ins>
<sub>Subscript Text</sub>
<sup>Superscript Text</sup>
```

### Tags Without Closing Tags

```html
<img src="image.jpg" alt="Image description"> <!-- Image tag -->
<br> <!-- Line break -->
<hr> <!-- Horizontal rule -->
<input type="text" name="example"> <!-- Input field -->
<meta charset="UTF-8"> <!-- Metadata tag -->
```

### Images

```html
<img src="image.jpg" alt="Description" width="300" height="200"> <!-- Image with alt text -->
<img src="image.jpg" alt="Description" loading="lazy"> <!-- Lazy loading image -->
```

### Lists

#### Unordered List

```html
<ul>
  <li>Item 1</li>
  <li>Item 2</li>
</ul>
```

#### Ordered List

```html
<ol>
  <li>First Item</li>
  <li>Second Item</li>
</ol>
```

#### Definition List

```html
<dl>
  <dt>Term 1</dt>
  <dd>Definition 1</dd>
</dl>
```

### Tables

```html
<table>
  <thead>
    <tr>
      <th>Header 1</th>
      <th>Header 2</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Data 1</td>
      <td>Data 2</td>
    </tr>
  </tbody>
</table>
```

### Forms

```html
<form action="/submit" method="POST">
  <input type="text" name="name" placeholder="Enter your name">
  <input type="email" name="email" placeholder="Enter your email">
  <input type="submit" value="Submit">
</form>
```

### Multimedia

#### Audio

```html
<audio controls>
  <source src="audio.mp3" type="audio/mp3">
  Your browser does not support the audio element.
</audio>
```

#### Video

```html
<video controls>
  <source src="video.mp4" type="video/mp4">
  Your browser does not support the video element.
</video>
```

### Semantic Tags

```html
<header>Header Content</header>
<footer>Footer Content</footer>
<article>Article Content</article>
<section>Section Content</section>
<nav>Navigation Links</nav>
<aside>Sidebar Content</aside>
<main>Main Content</main>
```

### HTML5 Input Types

```html
<input type="email" name="email"> <!-- Email input -->
<input type="tel" name="phone"> <!-- Telephone input -->
<input type="date" name="dob"> <!-- Date input -->
<input type="number" name="age"> <!-- Number input -->
<input type="range" name="volume"> <!-- Range slider -->
<input type="color" name="color"> <!-- Color picker -->
```

### Canvas

```html
<canvas id="myCanvas" width="200" height="200">
  Your browser does not support the canvas element.
</canvas>
```

### Inline Elements

```html
<span>Inline Text</span>
<a href="#">Clickable Link</a>
<strong>Bold Inline Text</strong>
<em>Italic Inline Text</em>
```

### Block Elements

```html
<div>Block Content</div>
<p>Paragraph Text</p>
<header>Header Block</header>
<footer>Footer Block</footer>
```

### Forms with Fieldsets and Legends

```html
<form action="/submit" method="POST">
  <fieldset>
    <legend>Personal Information</legend>
    <label for="name">Name:</label>
    <input type="text" id="name" name="name"><br>
    <label for="email">Email:</label>
    <input type="email" id="email" name="email"><br>
  </fieldset>
  <input type="submit" value="Submit">
</form>
```

### SVG Graphics

```html
<svg width="100" height="100">
  <circle cx="50" cy="50" r="40" stroke="black" stroke-width="3" fill="red" />
</svg>
```

### HTML Comments

```html
<!-- This is a comment. Comments are not displayed in the browser. -->
```

### Deprecated Tags (Do Not Use)

```html
<font color="red">Deprecated Text</font>
<center>Centered Text</center>
```

### Multimedia with Source Fallback

#### Audio

```html
<audio controls>
  <source src="audio.mp3" type="audio/mpeg">
  <source src="audio.ogg" type="audio/ogg">
  Your browser does not support the audio element.
</audio>
```

#### Video

```html
<video controls>
  <source src="video.mp4" type="video/mp4">
  <source src="video.webm" type="video/webm">
  Your browser does not support the video element.
</video>
```
