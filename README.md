# Alpine.js Mini Project 🚀

A simple web project built using **Alpine.js** for interactive and reactive UI components, like modals, clocks, accordions, and more.

---

## 🌟 Features

- ✅ Lightweight & Fast – Only ~10KB  
- ✅ Reactive UI – Easy state management with `x-data`  
- ✅ Declarative Syntax – `x-show`, `x-for`, `x-bind`, `x-on`  
- ✅ Interactive Components – Modals, dropdowns, tabs, toggles  
- ✅ Works with HTML & CSS – No build tools required  

---

## 📂 Project Structure

/alpinejs-project
├─ index.html # Main HTML page
├─ style.css # Custom styles
├─ script.js # Optional JS scripts
└─ README.md # Project documentation


---

## 🚀 Getting Started

1. Include Alpine.js in your HTML:

```html
<script defer src="https://cdn.jsdelivr.net/npm/alpinejs@3.x.x/dist/cdn.min.js"></script>
Create a reactive component:
<div x-data="{ count: 0 }">
  <p x-text="count"></p>
  <button @click="count++">Increment</button>
</div>
Open index.html in a browser – see the count update live! 🎉