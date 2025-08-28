
# HTML5 Beginner’s Guide: Important Tags with Examples

A beginner-friendly guide to **HTML5 tags** that every new web developer must know.  
This document covers the **tag name, attributes, purpose, and examples** of more than 30 commonly used HTML tags.

---

## 1. `<!DOCTYPE html>`
- **Purpose:** Defines the document type as HTML5.  
- **Usage:** Always the first line in an HTML document.  
- **Example:**
```html
<!DOCTYPE html>
```

---

## 2. `<html>`
- **Purpose:** Root element of an HTML page.  
- **Attributes:** `lang` (defines language).  
- **Example:**
```html
<html lang="en">
  ...
</html>
```

---

## 3. `<head>`
- **Purpose:** Contains metadata, title, and links to CSS/JS.  
- **Example:**
```html
<head>
  <title>My First Page</title>
  <meta charset="UTF-8">
</head>
```

---

## 4. `<title>`
- **Purpose:** Defines the page title (shown in browser tab, important for SEO).  
- **Example:**
```html
<title>Beginner HTML Guide</title>
```

---

## 5. `<meta>`
- **Purpose:** Provides metadata (SEO, charset, viewport).  
- **Common Attributes:**  
  - `charset="UTF-8"`  
  - `name="description"`  
  - `content="Beginner HTML Tutorial"`  
- **Example:**
```html
<meta name="description" content="Learn HTML5 important tags with examples">
```

---

## 6. `<link>`
- **Purpose:** Links external resources (CSS, icons).  
- **Example:**
```html
<link rel="stylesheet" href="style.css">
```

---

## 7. `<script>`
- **Purpose:** Embeds or links JavaScript code.  
- **Example:**
```html
<script src="app.js"></script>
```

---

## 8. `<body>`
- **Purpose:** Contains the visible content of the webpage.  
- **Example:**
```html
<body>
  <h1>Hello World</h1>
</body>
```

---

## 9. `<h1>` to `<h6>`
- **Purpose:** Headings (important for SEO & structure).  
- **Example:**
```html
<h1>Main Title</h1>
<h2>Subheading</h2>
```

---

## 10. `<p>`
- **Purpose:** Defines a paragraph.  
- **Example:**
```html
<p>This is a simple paragraph.</p>
```

---

## 11. `<a>`
- **Purpose:** Defines hyperlinks.  
- **Attributes:** `href`, `target`  
- **Example:**
```html
<a href="https://example.com" target="_blank">Visit Example</a>
```

---

## 12. `<img>`
- **Purpose:** Embeds images.  
- **Attributes:** `src`, `alt`, `width`, `height`  
- **Example:**
```html
<img src="image.jpg" alt="Sample Image" width="200">
```

---

## 13. `<br>`
- **Purpose:** Inserts a line break.  
- **Example:**
```html
Hello<br>World
```

---

## 14. `<hr>`
- **Purpose:** Inserts a horizontal line (divider).  
- **Example:**
```html
<hr>
```

---

## 15. `<strong>` & `<b>`
- **Purpose:** Bold text.  
- **Difference:** `<strong>` has semantic meaning (important text).  
- **Example:**
```html
<strong>Important</strong> <b>Bold</b>
```

---

## 16. `<em>` & `<i>`
- **Purpose:** Italic text.  
- **Difference:** `<em>` emphasizes text.  
- **Example:**
```html
<em>Emphasis</em> <i>Italic</i>
```

---

## 17. `<u>`
- **Purpose:** Underlines text.  
- **Example:**
```html
<u>Underlined Text</u>
```

---

## 18. `<mark>`
- **Purpose:** Highlights text.  
- **Example:**
```html
<mark>Important Note</mark>
```

---

## 19. `<small>`
- **Purpose:** Makes text smaller.  
- **Example:**
```html
<small>Copyright 2025</small>
```

---

## 20. `<ul>`, `<ol>`, `<li>`
- **Purpose:** Lists (unordered & ordered).  
- **Example:**
```html
<ul>
  <li>Item 1</li>
  <li>Item 2</li>
</ul>
<ol>
  <li>Step 1</li>
  <li>Step 2</li>
</ol>
```

---

## 21. `<div>`
- **Purpose:** Generic container for layout.  
- **Example:**
```html
<div class="container">Content</div>
```

---

## 22. `<span>`
- **Purpose:** Inline container for styling.  
- **Example:**
```html
<p>This is <span style="color:red">important</span>.</p>
```

---

## 23. `<table>`, `<tr>`, `<td>`, `<th>`
- **Purpose:** Display tabular data.  
- **Example:**
```html
<table border="1">
  <tr>
    <th>Name</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>Alice</td>
    <td>22</td>
  </tr>
</table>
```

---

## 24. `<form>`
- **Purpose:** Collects user input.  
- **Attributes:** `action`, `method`  
- **Example:**
```html
<form action="/submit" method="post">
  <input type="text" name="username">
  <button type="submit">Submit</button>
</form>
```

---

## 25. `<input>`
- **Purpose:** Collects user input (text, email, password, etc.).  
- **Example:**
```html
<input type="email" placeholder="Enter your email">
```

---

## 26. `<textarea>`
- **Purpose:** Multi-line text input.  
- **Example:**
```html
<textarea rows="4" cols="30"></textarea>
```

---

## 27. `<button>`
- **Purpose:** Clickable button.  
- **Example:**
```html
<button type="button">Click Me</button>
```

---

## 28. `<select>` & `<option>`
- **Purpose:** Dropdown list.  
- **Example:**
```html
<select>
  <option>Option 1</option>
  <option>Option 2</option>
</select>
```

---

## 29. `<header>`
- **Purpose:** Represents page header.  
- **Example:**
```html
<header>
  <h1>Website Title</h1>
</header>
```

---

## 30. `<nav>`
- **Purpose:** Defines navigation links.  
- **Example:**
```html
<nav>
  <a href="/">Home</a> | <a href="/about">About</a>
</nav>
```

---

## 31. `<section>`
- **Purpose:** Groups related content.  
- **Example:**
```html
<section>
  <h2>Introduction</h2>
  <p>Welcome to HTML5 guide.</p>
</section>
```

---

## 32. `<article>`
- **Purpose:** Self-contained content (blog, news).  
- **Example:**
```html
<article>
  <h2>News Title</h2>
  <p>Article content here.</p>
</article>
```

---

## 33. `<aside>`
- **Purpose:** Sidebar or secondary content.  
- **Example:**
```html
<aside>
  <p>Related links</p>
</aside>
```

---

## 34. `<footer>`
- **Purpose:** Represents page footer.  
- **Example:**
```html
<footer>
  <p>© 2025 My Website</p>
</footer>
```

---

## 35. `<iframe>`
- **Purpose:** Embeds another webpage.  
- **Example:**
```html
<iframe src="https://example.com" width="300" height="200"></iframe>
```

---

## 36. `<video>`
- **Purpose:** Embeds video.  
- **Example:**
```html
<video controls width="320">
  <source src="video.mp4" type="video/mp4">
</video>
```

---

## 37. `<audio>`
- **Purpose:** Embeds audio.  
- **Example:**
```html
<audio controls>
  <source src="song.mp3" type="audio/mpeg">
</audio>
```

---

## 38. `<canvas>`
- **Purpose:** For drawing graphics via JavaScript.  
- **Example:**
```html
<canvas id="myCanvas" width="200" height="100"></canvas>
```

---

## 39. `<svg>`
- **Purpose:** Scalable vector graphics.  
- **Example:**
```html
<svg width="100" height="100">
  <circle cx="50" cy="50" r="40" stroke="black" fill="red"/>
</svg>
```

---

## 40. `<progress>`
- **Purpose:** Shows progress of a task.  
- **Example:**
```html
<progress value="70" max="100"></progress>
```

---

## Final Notes
- Use **semantic tags** (`header`, `footer`, `article`, etc.) for better SEO and accessibility.  
- Always include **alt** attribute in images for screen readers.  
- Use headings in order (`h1` → `h2` → `h3`) for SEO optimization.  

---

✅ This README serves as a **beginner-friendly HTML5 reference** for web development and SEO best practices.
