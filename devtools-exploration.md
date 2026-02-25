# DevTools Exploration Report

## Website 1: https://example.com

**1. What HTML tags are used on the page?**

- `<html>`, `<head>`, `<title>`, `<meta>`, `<body>`, `<h1>`, `<p>`, `<a>`

**2. What is the page title?**

- `Example Domain`

**3. How many headings are there?**

- 1 heading (`<h1>`)

---

## Website 2: https://developer.mozilla.org

**1. Find the navigation menu - what tag is it wrapped in?**

- The main navigation menu is wrapped in a `<nav>` element.

**2. How is the search bar structured?**

- `<form>` element with:
  - `<input type="search">` for user queries
  - `<button type="submit">` to submit the search

**3. What happens when you hover over links (check the styles)?**

- The links change color (e.g., from default to blue or underline appears)  
- This is controlled by the `:hover` pseudo-class in CSS.

---

## Website 3: Any website of your choice (example: https://www.wikipedia.org)

**1. Identify 5 different HTML elements**

- `<html>`
- `<head>`
- `<title>`
- `<nav>`
- `<form>`
- `<input>`
- `<button>`
- `<img>`
- `<h1>` / `<h2>` / `<p>`  

**2. Find a form element and list its inputs**

- **Form:** Language search form on the homepage  
- **Inputs:**
  - `<input type="search" name="search">` – search box
  - `<button type="submit">` – search button

---

**Notes:**

- You can open Chrome DevTools with `F12` or `Ctrl+Shift+I` (Windows) / `Cmd+Option+I` (Mac)  
- Use the **Elements panel** to inspect the HTML structure  
- Use the **Styles panel** to check CSS rules, like hover effects  
- Use **Network or Console tabs** if needed to explore forms or scripts
