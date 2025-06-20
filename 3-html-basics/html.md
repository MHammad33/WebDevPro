# 🧱 HTML Basics

---

## 📘 What is HTML?

- **HTML** = _HyperText Markup Language_
- Standard language for building web pages
- Uses **tags** to define structure and content

---

## 🏷️ Common HTML Tags

```html
<h1>Heading 1</h1>
<html>
	<head>
		Metadata and links
	</head>
	<body>
		Main content of the page
	</body>
</html>
```

## 📂 Topics Covered

---

<details>
<summary>✅ 1. Introduction &nbsp;📄 <a href="./code/01_intro.html">View File</a></summary>

- `<h1>` to `<h6>` – Headings
- `<p>` – Paragraphs
- `<img>` – Images
- `<a>` – Anchor Tags (Links)
- `title` – Tooltips
- HTML Attributes:
  - `href` – for links
  - `alt` – for images
  - `src`, `target`, etc.

</details>

---

<details>
<summary>✅ 2. Headings & Lists  &nbsp;📄 <a href="./code/02_headings_lists.html">View File</a></summary>

### 🔤 Heading Levels

- `<h1>` = Most important
- `<h6>` = Least important

### 📝 Lists

- **Ordered List**: `<ol>` → numbered
- **Unordered List**: `<ul>` → bullets
- **List Items**: `<li>`

</details>

---

<details>
<summary>✅ 3. Block vs Inline Elements  &nbsp;📄 <a href="./code/03_block_inline.html">View File</a></summary>

| 🧱 Block Elements | 🧬 Inline Elements     |
| ----------------- | ---------------------- |
| Start on new line | Stay on same line      |
| Take full width   | Take only needed width |
| `<div>`, `<p>`    | `<span>`, `<a>`        |

</details>

---

<details>
<summary>✅ 4. Tables  &nbsp;📄 <a href="./code/04_tables.html">View File</a></summary>

### Table Structure Tags

- `<table>` – table
- `<tr>` – table row
- `<th>` – header cell
- `<td>` – data cell

</details>

---

<details>
<summary>✅ 5. Forms  &nbsp;📄 <a href="./code/05_forms.html">View File</a></summary>

### Purpose

- Collect **user input**

### Common Tags

- `<form>`, `<input>`, `<textarea>`
- `<label>`, `<button>`
- `<select>`, `<option>`

</details>

---

<details>
<summary>✅ 6. Semantics of HTML  &nbsp;📄 <a href="./code/06_semantics.html">View File</a></summary>

### Why Semantic Tags?

- Adds **meaning** to structure
- Improves **SEO** and **accessibility**

### Examples

- Layout: `<header>`, `<footer>`, `<main>`, `<nav>`
- Sections: `<section>`, `<article>`, `<aside>`

</details>

---

<details>
<summary>✅ 7. Media &nbsp;📄 <a href="./code/07_media.html">View File</a></summary>

### 🎥 Media Tags in HTML

- `<img>` – Displays images
- `<audio>` – Embeds audio files
- `<video>` – Embeds video files
- `<source>` – Specifies media sources
- `<track>` – Provides subtitles and captions

### 🔧 Useful Attributes

- `src`, `alt`, `controls`, `autoplay`, `loop`, `muted`, `poster`

</details>

---

<details>
<summary>✅ 8. ARIA (Accessibility)  &nbsp;📄 <a href="./code/08_accessiblity.html">View File</a></summary>

### What is ARIA?

- **Accessible Rich Internet Applications**
- Helps **screen readers** understand dynamic content

### Common Attributes

- `role`, `aria-label`, `aria-hidden`, `aria-live`

</details>
