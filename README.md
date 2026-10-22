*Chrome => DevTools => Console*

* Remove borders

### OpenGraph image

inspect(document.querySelector('.opengraph'))

### Favicon

inspect(document.querySelector('.favicon'))

### Logo

inspect(document.querySelector('.logo'))

### Profile

inspect(document.querySelector('.profile'))

- Cmd + Shift + P
- Capture node screenshot

---

**stars import**

The HTML loads `data.js` using a script tag. That file stores the star gradients in a JavaScript string, then uses `document.documentElement.style.setProperty('--stars', stars.trim())` to set a CSS custom property on the root HTML element. The stylesheet accesses it through `var(--stars)`. Using `background: var(--stars), var(--brand-gradient);` places the stars above the background gradient. CSS doesn’t directly import JavaScript; JavaScript supplies the variable that CSS reads.

---

