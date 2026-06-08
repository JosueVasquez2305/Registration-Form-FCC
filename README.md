# Registration Form - freeCodeCamp Practice

A clean, semantic, and responsive registration form built as part of the freeCodeCamp Responsive Web Design certification. This project focuses on mastering HTML form structures, input validations, and custom CSS styling for user interfaces.

## 🚀 Project Overview

The goal of this project was to build a multi-section registration form that handles various types of user data input securely and accessibly, ensuring a smooth user experience.

## 🛠️ Technologies Used

* **HTML5:** Semantic elements (`<form>`, `<fieldset>`, `<legend>`, `<label>`) and input attributes (`required`, `pattern`, `min`, `max`).
* **CSS3:** Custom styling, layout management (`width`, `margin: auto`, `min-height`), and attribute selectors (`input[type="submit"]`).

## 🔑 Key Features & Concepts Learned

* **Form Semantics:** Grouping related data fields using `<fieldset>` and providing accessible captions with `<legend>`.
* **Input-Label Association:** Properly linking `<label>` elements to their respective `<input>` fields using the `for` and `id` attributes.
* **Input Architecture:** Implementing unique `id` and `name` attributes for submittable elements to ensure data packages correctly for server transmission.
* **Data Validation:** Enforcing client-side validation using the `required` attribute, numeric limits (`min`/`max`), and regular expressions (`pattern`).
* **UI Customization:** Styling interactive fields (`input`, `textarea`, `select`), custom styling for file uploads (`input[type="file"]`), and implementing inline layouts for checkboxes and radio buttons.

## 📁 File Structure

```text
├── index.html   # HTML5 form structure and semantic elements
└── styles.css   # Document layout, colors, and responsive constraints
```


🧠 Reflection & Learnings
During the development of this form, I mastered the distinction between the id and name attributes within form fields. While id serves as a unique identifier for DOM targeting and layout association, name acts as the data key that travels to the server upon submission. This project significantly improved my understanding of web accessibility (A11y) and user interface design constraints.