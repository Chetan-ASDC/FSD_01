# Lecture Content: HTML Basics

## 1. Introduction to HTML

**HTML (HyperText Markup Language)** is the standard markup language used to create and structure content on the web. It defines the structure of web pages using elements such as headings, paragraphs, images, links, and forms.

**Key points:**

* HTML is not a programming language; it is a markup language.
* It works alongside CSS (styling) and JavaScript (interactivity).
* Current standard: **HTML5**.

---

## 2. How the Web Works

Understanding how HTML fits into the web ecosystem:

1. **User enters a URL** in a browser
2. **Browser sends a request** to a web server (HTTP/HTTPS)
3. **Server responds** with HTML, CSS, JS, and other assets
4. **Browser renders** the HTML into a visual web page

**Key components:**

* **Client:** Web browser (Chrome, Firefox, Edge)
* **Server:** Hosts website files
* **Protocol:** HTTP / HTTPS

---

## 3. What is HTML5

HTML5 is the latest major version of HTML, designed to support modern web applications.

**Features of HTML5:**

* Semantic elements (`<header>`, `<footer>`, `<article>`, `<section>`)
* Native audio and video support
* Improved form controls
* Better accessibility and SEO
* No need for plugins (like Flash)

---

## 4. Basic HTML Document Structure

Every HTML document follows a standard structure:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>My First Page</title>
</head>
<body>
    <h1>Hello World</h1>
    <p>This is my first HTML page.</p>
</body>
</html>
```

**Explanation:**

* `<!DOCTYPE html>`: Declares HTML5
* `<html>`: Root element
* `<head>`: Metadata (not visible on page)
* `<body>`: Visible content

---

## 5. Head Elements in Detail

The `<head>` section contains metadata and resources.

Common head elements:

* `<title>` – Page title (shown in browser tab)
* `<meta charset="UTF-8">` – Character encoding
* `<meta name="viewport">` – Responsive design
* `<meta name="description">` – SEO description
* `<link>` – External CSS files
* `<style>` – Internal CSS
* `<script>` – JavaScript files

Example:

```html
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Basics</title>
</head>
```

---

## 6. Creating Your First HTML Page

Steps:

1. Open a text editor (VS Code, Notepad++)
2. Create a file named `index.html`
3. Write basic HTML structure
4. Save the file
5. Open it in a web browser

Simple example:

```html
<h1>Welcome</h1>
<p>This is my first webpage.</p>
```

---

## 7. HTML Best Practices

### Structure & Readability

* Use proper indentation
* Keep code clean and organized
* Use comments when necessary

### Semantic HTML

* Prefer semantic tags over generic `<div>`
* Improves accessibility and SEO

### Accessibility

* Use `alt` attributes for images
* Use proper heading order (`h1` to `h6`)
* Label form inputs

### Performance & Maintainability

* Keep HTML simple
* Separate structure (HTML), style (CSS), behavior (JS)
* Avoid inline styles when possible

### Validation

* Validate HTML using W3C Validator
* Fix errors and warnings

---

## 8. Summary

* HTML defines the structure of web pages
* HTML5 introduces semantic and modern features
* Proper document structure is essential
* `<head>` elements control metadata and behavior
* Following best practices improves quality and accessibility

---

