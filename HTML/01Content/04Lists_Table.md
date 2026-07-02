# Lecture 4: Lists, Tables & Semantic HTML

---

## 1. Introduction

Lists, tables, and semantic HTML elements are used to organize content clearly and meaningfully. Proper use improves readability, accessibility, and search engine optimization.

---

## 2. Lists in HTML

Lists are used to group related items.

---

### 2.1 Ordered List (`<ol>`)

An ordered list displays items in a numbered sequence.

```html
<ol>
  <li>HTML</li>
  <li>CSS</li>
  <li>JavaScript</li>
</ol>
```

Use cases:

* Steps or procedures
* Rankings

---

### 2.2 Unordered List (`<ul>`)

An unordered list displays items with bullets.

```html
<ul>
  <li>Home</li>
  <li>About</li>
  <li>Contact</li>
</ul>
```

Use cases:

* Navigation menus
* Feature lists

---

### 2.3 Description List (`<dl>`)

A description list is used for terms and their descriptions.

```html
<dl>
  <dt>HTML</dt>
  <dd>HyperText Markup Language</dd>

  <dt>CSS</dt>
  <dd>Cascading Style Sheets</dd>
</dl>
```

Use cases:

* Definitions
* FAQs

---

## 3. Tables in HTML

Tables are used to display tabular data.

---

### 3.1 Basic Table Structure

```html
<table>
  <tr>
    <th>Name</th>
    <th>Course</th>
  </tr>
  <tr>
    <td>Alice</td>
    <td>Web Development</td>
  </tr>
</table>
```

### Table Tags

* `<table>` – Defines a table
* `<tr>` – Table row
* `<th>` – Table header cell
* `<td>` – Table data cell

---

### 3.2 Table Sections

```html
<table>
  <thead>
    <tr>
      <th>Subject</th>
      <th>Marks</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>HTML</td>
      <td>85</td>
    </tr>
  </tbody>
  <tfoot>
    <tr>
      <td>Total</td>
      <td>85</td>
    </tr>
  </tfoot>
</table>
```

* `<thead>` – Header section
* `<tbody>` – Main content
* `<tfoot>` – Summary/footer

---

### 3.3 Table Accessibility Basics

* Use `<th>` for headings
* Use `scope="col"` or `scope="row"`
* Avoid tables for layout

```html
<th scope="col">Name</th>
```

---

## 4. Semantic HTML Tags

Semantic elements clearly describe their meaning.

---

### Common Semantic Tags

```html
<header>Page header</header>
<nav>Navigation links</nav>
<section>Page section</section>
<article>Independent content</article>
<aside>Sidebar content</aside>
<footer>Page footer</footer>
```

---

## 5. Semantic vs Non-Semantic Tags

### Semantic Tags

* Convey meaning
* Improve accessibility
* Help search engines

Examples:

```html
<header>, <article>, <footer>
```

### Non-Semantic Tags

* No inherent meaning
* Used mainly for styling

Examples:

```html
<div>, <span>
```

---

## 6. Why Semantic HTML Matters

### Benefits

* Better SEO
* Improved accessibility (screen readers)
* Cleaner, maintainable code
* Clear content structure

---

## 7. Lecture Summary

* Lists organize related items
* Tables present structured data
* Semantic HTML gives meaning to content
* Proper semantics improve SEO and accessibility

---

**End of Lecture 4**
