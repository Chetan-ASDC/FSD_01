# Lecture 5: Forms, Inputs & Multimedia

---

## 1. Introduction

Forms allow users to send data to a server, while multimedia elements enhance user engagement through audio and video content. This lecture introduces form creation, input controls, validation, accessibility, and multimedia usage in HTML.

---

## 2. Form Basics

HTML forms are created using the `<form>` tag.

```html
<form action="submit.php" method="post">
  <!-- form controls -->
</form>
```

### Common Form Attributes

* **action** – URL where form data is sent
* **method** – HTTP method (`get` or `post`)

---

## 3. Input Elements

### `<input>` Tag

The `<input>` element is used to collect user data.

#### Common Input Types

```html
<input type="text" placeholder="Enter name">
<input type="email" placeholder="Enter email">
<input type="password" placeholder="Enter password">
<input type="radio" name="gender"> Male
<input type="checkbox"> Accept terms
<input type="file">
<input type="submit" value="Submit">
```

---

## 4. Other Form Controls

### Label (`<label>`)

```html
<label for="email">Email:</label>
<input type="email" id="email">
```

### Textarea (`<textarea>`)

```html
<textarea rows="4" cols="40"></textarea>
```

### Select, Option (`<select>`, `<option>`)

```html
<select>
  <option>HTML</option>
  <option>CSS</option>
</select>
```

---

## 5. Form Validation Attributes

HTML provides built-in validation attributes.

```html
<input type="text" required placeholder="Username">
<input type="text" pattern="[A-Za-z]{3,}">
```

### Common Validation Attributes

* `required`
* `placeholder`
* `pattern`
* `min`, `max`, `maxlength`

---

## 6. Accessibility in Forms

### Best Practices

* Always use `<label>` with inputs
* Group related fields using `<fieldset>` and `<legend>`
* Provide clear error messages

```html
<label for="name">Name</label>
<input id="name" type="text" required>
```

---

## 7. Multimedia Tags

Multimedia elements allow embedding audio and video directly in web pages.

---

### Audio (`<audio>`)

```html
<audio controls>
  <source src="song.mp3" type="audio/mpeg">
</audio>
```

---

### Video (`<video>`)

```html
<video controls width="400">
  <source src="movie.mp4" type="video/mp4">
</video>
```

---

### `<embed>` and `<iframe>`

```html
<embed src="file.pdf" width="400" height="300">
```

```html
<iframe src="https://www.youtube.com/embed/VIDEO_ID"></iframe>
```

---

## 8. Best Practices for Multimedia Usage

* Use controls for accessibility
* Provide captions or transcripts
* Optimize file size
* Avoid auto-play

---

## 9. HTML Validation

HTML validation checks code correctness using tools like the **W3C Validator**.

Benefits:

* Detects errors
* Improves browser compatibility
* Enhances accessibility

---

## 10. Next Steps: CSS & JavaScript Overview

* **CSS** – Used for styling and layout
* **JavaScript** – Adds interactivity and logic

Together with HTML, they form the core of web development.

---

## 11. Lecture Summary

* Forms collect user data using inputs
* HTML provides built-in validation
* Accessibility improves usability
* Multimedia enriches web content
* CSS and JavaScript are the next learning steps

---

**End of Lecture 5**
