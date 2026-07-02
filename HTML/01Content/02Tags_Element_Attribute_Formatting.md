# Lecture 2: Tags, Elements, Attributes & Text Formatting

---

## 1. Tags vs Elements vs Attributes

### HTML Tags

An **HTML tag** is a keyword enclosed in angle brackets used to define content.

```html
<p>
```

* Usually written in pairs: opening `<p>` and closing `</p>`
* Some tags are self-closing (void elements): `<br>`, `<img>`, `<hr>`

### HTML Elements

An **HTML element** consists of:

* Opening tag
* Content
* Closing tag

```html
<p>This is a paragraph.</p>
```

### HTML Attributes

**Attributes** provide additional information about an element.

```html
<img src="photo.jpg" alt="Profile photo">
```

* Written inside the opening tag
* Usually in `name="value"` format

---

## 2. Headings

HTML provides six levels of headings used to define page structure.

```html
<h1>Main Heading</h1>
<h2>Sub Heading</h2>
<h3>Section Heading</h3>
<h4>Sub Section</h4>
<h5>Minor Heading</h5>
<h6>Least Important Heading</h6>
```

### Best Practices

* Use only one `<h1>` per page
* Follow proper hierarchy (`h1 → h2 → h3`)
* Do not use headings only for visual styling

---

## 3. Paragraphs

Paragraphs are used to display blocks of text.

```html
<p>This is a paragraph.</p>
```

### Key Points

* Browsers add spacing automatically
* Use `<br>` for line breaks inside a paragraph

---

## 4. Text Formatting Tags

Formatting tags are used to emphasize or style text content.

```html
<b>Bold</b>
<strong>Strong Importance</strong>
<i>Italic</i>
<em>Emphasis</em>
<u>Underline</u>
<mark>Highlighted</mark>
<small>Small Text</small>
<sup>Superscript</sup>
<sub>Subscript</sub>
```

### Note

* Prefer semantic tags like `<strong>` and `<em>`
* Improves accessibility and SEO

---

## 5. HTML Entities

HTML entities are used to display reserved or special characters.

```html
&lt;   &gt;   &amp;   &copy;   &nbsp;
```

### Common Entities

* `<` → `&lt;`
* `>` → `&gt;`
* `&` → `&amp;`
* © → `&copy;`
* Non-breaking space → `&nbsp;`

---

## 6. Block vs Inline Elements

### Block-level Elements

* Start on a new line
* Take full available width

Examples:

```html
<div>, <p>, <h1>, <ul>, <section>
```

### Inline Elements

* Do not start on a new line
* Take only required width

Examples:

```html
<span>, <a>, <img>, <strong>, <em>
```

---

## 7. Accessibility Basics

Web accessibility ensures that web content is usable by all users, including people with disabilities.

### Key Accessibility Practices

* Use semantic HTML elements
* Provide meaningful `alt` text for images
* Maintain correct heading order
* Avoid using formatting tags only for visuals

```html
<img src="logo.png" alt="Company logo">
```

### Benefits of Accessibility

* Better user experience
* Improved SEO
* Legal and ethical compliance

---

## 8. Lecture Summary

* Tags define structure, elements contain content, attributes add information
* Headings and paragraphs organize text
* Formatting tags enhance readability
* Entities display special characters
* Block and inline elements behave differently
* Accessibility improves inclusiveness and quality

---

