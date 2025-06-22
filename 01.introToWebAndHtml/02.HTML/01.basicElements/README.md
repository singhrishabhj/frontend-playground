# Basic Elements

Here is the **cleaned version of your HTML Agenda (Part 2)** without any emoticons, formatted professionally for use in your `README.md` file or study notes:

---

# HTML Agenda – Part 2

## Topics Covered

* Headings
* Paragraphs
* Buttons
* Anchor Tags (Links)
* Images
* Line Breaks
* Lists (Ordered & Unordered)
* HTML Attributes
* Table Structure

---

## 01. Headings

HTML provides 6 levels of headings: `<h1>` to `<h6>`

* `<h1>` – Main title
* `<h2>` – Major section headings
* `<h3>` to `<h6>` – Subsections

Example:

```html
<h1>I am heading</h1>
<h2>I am heading</h2>
<h3>I am heading</h3>
...
<h6>I am heading</h6>
```

---

## 02. Paragraphs

Defined using the `<p>` tag. Used to display blocks of text.

Example:

```html
<p>This is a paragraph of text.</p>
<p>Lorem ipsum dolor sit amet...</p>
```

---

## 03. Buttons

Created using the `<button>` tag. Used for user interactions.

Example:

```html
<button>Click Me</button>
<button disabled="disabled">Disabled Button</button>
```

---

## 04. Anchor Tags (Links)

Used to create hyperlinks.

Examples:

```html
<a href="https://www.google.com/">Visit Google</a>
<a href="https://picsum.photos" target="_blank">Open in New Tab</a>
<a href="./image.jpg" download>Download Image</a>
```

### Anchor Tag Attributes

| Attribute         | Description                           |
| ----------------- | ------------------------------------- |
| `href`            | URL or file path to navigate/download |
| `target="_blank"` | Opens link in a new tab               |
| `download`        | Prompts download of file              |

---

## 05. Images

Inserted using the `<img>` tag.

Example:

```html
<img src="https://picsum.photos/200/300" alt="Random Image" height="200px">
```

### Image Attributes

| Attribute          | Description                               |
| ------------------ | ----------------------------------------- |
| `src`              | Image URL or path                         |
| `alt`              | Alternate text for accessibility/fallback |
| `height` / `width` | Sets image dimensions in pixels           |

### Image Types

* **JPG**: Common for photos with visible backgrounds
* **PNG**: Common for images with transparent backgrounds

---

## 06. Line Breaks

Use `<br>` to break a line of text.

Example:

```html
<p>Hello<br>World</p>
```

---

## 07. Lists

### Unordered List

```html
<ul>
  <li>Apple</li>
  <li>Oranges</li>
</ul>
```

### Ordered List

```html
<ol>
  <li>HTML</li>
  <li>CSS</li>
</ol>
```

### Ordered List with `type` Attribute

```html
<ol type="A"> <!-- Uppercase letters -->
<ol type="i"> <!-- Lowercase Roman numerals -->
```

---

## 08. HTML Attributes

Attributes are included in the opening tag of an element.

Examples:

```html
<img src="image.jpg" alt="description" width="300" height="200">
<a href="https://example.com" target="_blank" title="Visit">Click</a>
```

### Common Attributes by Tag

| Tag        | Common Attributes                     |
| ---------- | ------------------------------------- |
| `<img>`    | `src`, `alt`, `width`, `height`       |
| `<a>`      | `href`, `target`, `download`, `title` |
| `<button>` | `disabled`                            |

---

## 09. HTML Tables

### Table Structure Example

```html
<table>
  <thead>
    <tr><th>NO</th><th>Name</th><th>Subject</th><th>Marks</th></tr>
  </thead>
  <tbody>
    <tr><td>1</td><td>Jasbir</td><td>English</td><td>80</td></tr>
    ...
  </tbody>
</table>
```

### Table Tags Explained

| Tag       | Purpose                       |
| --------- | ----------------------------- |
| `<table>` | Defines the table container   |
| `<thead>` | Header section of the table   |
| `<tbody>` | Body/content section          |
| `<tr>`    | Table row                     |
| `<th>`    | Header cell (bold by default) |
| `<td>`    | Standard data cell            |

---

## Assignment Link

Please complete the assignment questions based on the above notes:
[GitHub Assignment Questions](https://github.com/Jasbir96/Algoprep_cohort_1/tree/main/Lec_2_HTML_1/questions)

---

If you'd like this as a downloadable `README.md`, or want folder commands for this structure, I can generate that for you. Just let me know.
