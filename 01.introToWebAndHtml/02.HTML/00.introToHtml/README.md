# HTML Intro Agenda – Structured Topics

### **01. What is HTML?**

* Definition: HyperText Markup Language
* Purpose: Tells browsers how to structure web pages
* Visual comparison: Webpage before and after HTML

---

### **02. HTML Elements & Their Anatomy**

* Example: `<p>My cat is very grumpy</p>`
* Parts:

  * Opening tag (`<p>`)
  * Content (`My cat is very grumpy`)
  * Closing tag (`</p>`)
* Common beginner error: Missing closing tags

---

### **03. Anatomy of an HTML Document**

* Basic boilerplate:

```html
<!DOCTYPE html>
<html lang="en-US">
  <head>
    <title>HTML in one shot</title>
  </head>
  <body>
    <p>Namaste World</p>
  </body>
</html>
```

* Tags explained:

  1. `<!DOCTYPE html>` – Defines HTML5
  2. `<html>` – Root element
  3. `<head>` – Meta information, styles, SEO
  4. `<title>` – Page title (shown in browser tab)
  5. `<body>` – Visible content of the page

---

### **04. Writing HTML Code in VS Code**

* Steps:

  1. Create `index.html` inside a folder
  2. Type `!` and press `Enter` to generate boilerplate
  3. Use Live Server extension to run the file
  4. Open HTML file directly from file system (double-click)

---

### **05. HTML Structure Revisited**

* `<html lang="en">` – HTML document in English
* Two major parts:

  * `<head>` – invisible metadata
  * `<body>` – visible content

---

### **06. Meta Tags in HTML**

* `<meta charset="UTF-8">`: Handles multilingual characters
* `<meta name="viewport" content="width=device-width, initial-scale=1.0">`: Responsive design for mobile/tablet
* Importance of metadata for SEO and browser behavior

---

### **07. Case Insensitivity in HTML**

* HTML tags are case-insensitive:

  * `<HEAD>`, `<Head>`, `<head>` = same result
* Best practice: always use lowercase for tags

---

### **08. Common Tags**

* **Headings (`<h1>` to `<h6>`)**

  * Hierarchical content structure
* **Paragraph (`<p>`)**

  * Descriptive content
  * Use `lorem` abbreviation for dummy text (Emmet)
* **Image (`<img>`)**

  * Self-closing tag
  * Uses `src` and `alt` attributes
  * `alt` is helpful for accessibility and fallback
* **Anchor (`<a>`)**

  * Creates hyperlinks
  * Attributes: `href`, `target`, etc.
  * Connects resources on the web

---
