# How to Write an HTML Boilerplate

In web development, an **HTML boilerplate** provides a basic structure for any HTML document. This foundation includes the necessary elements for creating a valid and accessible webpage. Below, we'll go through the essential components of an HTML boilerplate, complete with explanations and examples.

## Basic Structure of an HTML Document

Every HTML document should follow a standard structure. This includes a `<!DOCTYPE>`, the opening and closing `<html>` tags, and nested sections for `head` and `body`. Here’s the **basic syntax** you’ll see in almost any HTML boilerplate:

1. **DOCTYPE**: Declares the HTML version.
2. **HTML Tag**: Wraps the entire HTML document.
3. **Head Section**: Contains meta information, links, and styles.
4. **Body Section**: Holds the visible content of the page.

**Example:**

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Your Page Title</title>
  </head>
  <body>
    <!-- Your content goes here -->
  </body>
</html>
```

> **Tip:** Always specify `lang="en"` (or the language you're using) within the `<html>` tag to improve accessibility and SEO.

## Head Section Elements

The `<head>` section is essential for defining the document’s metadata, linking stylesheets, and more. Below are some common elements:

- **Charset**: Defines character encoding.
- **Viewport**: Controls layout on different devices.
- **Title**: Specifies the title displayed on the browser tab.
- **Link**: Links external resources like stylesheets.

**Example of a Complete `<head>` Section:**

```html
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>My HTML Boilerplate</title>
  <link rel="stylesheet" href="styles.css" />
</head>
```

For a comprehensive guide to the `<head>` section, check out the [MDN Documentation on HTML Head Elements](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/head).

## Body Section Elements

The `<body>` section contains all visible elements that users interact with. Here are some common tags used in the body:

1. **Headers**: `<h1>`, `<h2>`, etc., create headings and subheadings.
2. **Paragraphs**: `<p>` for paragraph text.
3. **Links**: `<a href="#">Link text</a>` for navigation.
4. **Images**: `<img src="path/to/image.jpg" alt="Description">` for displaying images.

**Example of a Body Section:**

```html
<body>
  <h1>Welcome to My Website</h1>
  <p>This is a sample paragraph on my homepage.</p>
  <a href="https://www.example.com">Visit Example.com</a>
  <img src="https://via.placeholder.com/150" alt="Placeholder Image" />
</body>
```

### Sample Boilerplate with All Elements

Here’s a complete example, combining the head and body sections to form a full HTML boilerplate:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>HTML Boilerplate Example</title>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    <h1>Hello, World!</h1>
    <p>This is a basic HTML boilerplate.</p>
    <a href="https://developer.mozilla.org">Learn more about HTML on MDN</a>
    <img src="https://via.placeholder.com/600x300" alt="Example Banner Image" />
  </body>
</html>
```

