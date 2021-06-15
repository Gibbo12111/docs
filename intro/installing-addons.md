---
title: Installing Addons
description: testing the things wow amzizng
---

# Wow amazing

```html
<button>Button 1</button>
<button>Button 2</button>
<button>Button 3</button>
<button>Button 4</button>
```

```js
const buttons = document.querySelectorAll('button');

buttons.forEach(button => {
  button.addEventListener('click', e => {
    alert(`${e.textContent} has been clicked`)
  })
})
```

```css
body {
  background: #222;
  margin: 0;
  padding: 0;
  font-family: 'Arial';
  font-weight: 400;
  color: #fff;
 }
button {
  background: #444;
  border-radius: 4px;
  color: #fff;
  border: none;
  cursor: pointer;
  padding: 8px 16px;
 }
 button:hover {
  background: #484848;
 }
 button:focus {
  background: #545454;
 }
 ```
