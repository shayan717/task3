## DRY Principle
- **Definition:** *Don’t Repeat Yourself* — aim to reduce code duplication by reusing logic.  
- **Goal:** Make code easier to maintain and update.  
- **Example:** Put repeated logic in a function or class instead of writing it multiple times.

---

## SOLID Principles
1. **S**ingle Responsibility Principle — a class/module should have **one reason to change**.  
2. **O**pen/Closed Principle — software should be **open for extension, closed for modification**.  
3. **L**iskov Substitution Principle — subclasses should be **replaceable** for their base classes without breaking functionality.  
4. **I**nterface Segregation Principle — many **small, specific interfaces** are better than one large, general interface.  
5. **D**ependency Inversion Principle — depend on **abstractions, not concrete implementations**.

---

## Default Export vs Named Export in JavaScript

### Default Export
- You export **one main thing** from a file.  
- When importing, you can name it **anything you want**.  
- Commonly used when a module has a **single responsibility**.

### Named Export (Normal Export)
- You can export **multiple things** from a file.  
- When importing, you **must** use the **exact same name** (or use `as` to rename).  
- Good when you have **multiple related utilities** in one file.

---

## Handlebars
Handlebars (often written as `.hbs`) is a templating engine for HTML.  
It lets you write HTML with placeholders that get replaced with real data before sending the page to the browser.

### How It Works
1. You write a `.hbs` template with placeholders like `{{name}}`.  
2. Your server (Node.js + Express, for example) sends real data to that template.  
3. Handlebars replaces the placeholders with actual values and returns final HTML.
