# Accessibility Audit Report

## Project: iyf-s10-week-01
## Student: Josephine Wangui
## Date: [25,02,2026]

---

# Tools Used

- Chrome DevTools Lighthouse (Accessibility Audit)
- WAVE Web Accessibility Evaluation Tool

---

# 1️⃣ Issues Found

## 1. Missing alt Text on Images
Some images did not include `alt` attributes, making them inaccessible to screen readers.

Example (Before):
```html
<img src="profile.jpg">
