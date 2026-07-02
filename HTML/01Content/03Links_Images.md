# Lecture 3: Links, Navigation & Images

---

## 1. Introduction

Links and images are essential building blocks of the web. Links allow users to navigate between pages and resources, while images enhance communication, usability, and visual appeal.

---

## 2. Anchor Tag (`<a>`) and Attributes

The **anchor tag** is used to create hyperlinks.

```html
<a href="https://www.example.com">Visit Example</a>
```

### Common Attributes

* **href** – Specifies the destination URL
* **target** – Defines where the link opens
* **title** – Displays additional information on hover

```html
<a href="page.html" target="_blank" title="Go to page">Open Page</a>
```

---

## 3. Types of Links

### Internal Links

Links to pages within the same website.

```html
<a href="about.html">About Us</a>
```

### External Links

Links to other websites.

```html
<a href="https://openai.com" target="_blank">OpenAI</a>
```

### Email Links

```html
<a href="mailto:info@example.com">Send Email</a>
```

### Phone Links

```html
<a href="tel:+911234567890">Call Us</a>
```

---

## 4. Page Navigation and Bookmarks (IDs)

IDs can be used to navigate to specific sections within the same page.

```html
<a href="#contact">Go to Contact</a>

<h2 id="contact">Contact Us</h2>
```

### Use Cases

* Long pages
* FAQs
* Documentation pages

---

## 5. Image Tag (`<img>`) and Attributes

Images are embedded using the `<img>` tag.

```html
<img src="photo.jpg" alt="Student in computer lab">
```

### Common Attributes

* **src** – Path to the image
* **alt** – Alternative text
* **width** – Image width
* **height** – Image height

```html
<img src="logo.png" alt="College logo" width="200" height="100">
```

---

## 6. Importance of Alt Text (Accessibility & SEO)

The `alt` attribute:

* Helps screen readers describe images
* Displays text if image fails to load
* Improves search engine optimization (SEO)

```html
<img src="chart.png" alt="Bar chart showing yearly sales growth">
```

---

## 7. Image Formats

| Format     | Use Case                            |
| ---------- | ----------------------------------- |
| JPG / JPEG | Photographs, complex images         |
| PNG        | Transparent backgrounds             |
| SVG        | Icons, logos (scalable)             |
| WebP       | High quality with smaller file size |

---

## 8. Image Maps (`<map>` and `<area>`)

Image maps allow clickable areas within an image.

```html
<img src="campus.png" usemap="#campusmap" alt="Campus map">

<map name="campusmap">
  <area shape="rect" coords="34,44,270,350" href="library.html" alt="Library">
</map>
```

---

## 9. Basic Folder Structure for Assets

Organizing files improves maintainability.

```text
project-folder/
│
├── index.html
├── about.html
├── css/
│   └── style.css
├── images/
│   ├── logo.png
│   └── banner.jpg
└── js/
    └── script.js
```

---

## 10. Best Practices

* Use relative links for internal pages
* Always include meaningful `alt` text
* Optimize images for performance
* Use modern image formats when possible

---

## 11. Lecture Summary

* `<a>` tag creates hyperlinks using `href`
* IDs enable page-level navigation
* `<img>` embeds images with accessibility support
* Proper image formats and structure improve performance

---

