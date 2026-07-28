<div align="center">

# 💻 Live Code Editor

### Write HTML, CSS and JavaScript — then preview the result instantly

A lightweight browser-based code editor with separate HTML, CSS and JavaScript panels, live output rendering, copy controls and fullscreen preview.

[View Repository](https://github.com/Rachana0106/live-code-editor)

</div>

---

## 📖 About the Project

**Live Code Editor** is a frontend web application that allows users to write HTML, CSS and JavaScript code in separate editor panels and display the combined result inside an output window.

The project is designed as a simple practice environment for beginners who want to test small web-development ideas without creating multiple files every time.

It works like a mini browser-based coding playground.

---

## 🎯 Project Objective

The main goal of this project was to practise:

- DOM manipulation
- JavaScript event handling
- Working with iframe content
- Executing user-written code
- Clipboard functionality
- Fullscreen interface controls
- Building a practical frontend tool

---

## ✨ Main Features

- Separate HTML editor
- Separate CSS editor
- Separate JavaScript editor
- Output preview inside an iframe
- Run and render user-written code
- Copy HTML code
- Copy CSS code
- Copy JavaScript code
- Fullscreen output preview
- Clean code-editor interface
- Technology icons for each editor
- No external framework required

---

## ⚙️ How It Works

The editor takes code from three different input panels:

```text
HTML input
     │
CSS input
     │
JavaScript input
     │
     ▼
Output iframe
```

When the user clicks the output button:

1. HTML is inserted into the iframe body.
2. CSS is inserted into the iframe head inside a `<style>` element.
3. JavaScript is executed inside the iframe.
4. The final result appears in the output section.

---

## 🧩 Editor Sections

### HTML Editor

Used to write the structure of the webpage.

Example:

```html
<h1>Hello World</h1>
<p>This is my live code editor.</p>
```

### CSS Editor

Used to style the HTML content.

Example:

```css
body {
  font-family: Arial, sans-serif;
  text-align: center;
}

h1 {
  color: purple;
}
```

### JavaScript Editor

Used to add logic and interactivity.

Example:

```javascript
document.querySelector("h1").addEventListener("click", () => {
  alert("Heading clicked!");
});
```

---

## 🛠️ Technologies Used

<div align="left">

<img src="https://skillicons.dev/icons?i=html,css,js,git,github,vscode" alt="Technologies used"/>

</div>

- **HTML5** — Application structure
- **CSS3** — Layout and styling
- **JavaScript** — Editor functionality and interactions
- **iframe** — Code preview environment
- **Clipboard API** — Copy-code functionality
- **Git** — Version control
- **GitHub** — Source-code hosting
- **VS Code** — Development environment

---

## 📁 Project Structure

```text
live-code-editor/
│
├── index.html
├── style.css
├── script.js
│
├── assets/
│   ├── html-logo.png
│   ├── css-logo.png
│   ├── javascript-logo.png
│   ├── copy.svg
│   ├── save.svg
│   └── full.svg
│
└── README.md
```

---

## 🚀 How to Run the Project

### Method 1: Open Directly

1. Download or clone the repository.
2. Open the project folder.
3. Double-click `index.html`.
4. The editor will open in your browser.

### Method 2: Clone with Git

```bash
git clone https://github.com/Rachana0106/live-code-editor.git
```

Open the project folder:

```bash
cd live-code-editor
```

Then open `index.html` in your browser.

### Method 3: Use VS Code Live Server

1. Open the folder in VS Code.
2. Install the **Live Server** extension.
3. Right-click `index.html`.
4. Select **Open with Live Server**.

---

## 🖥️ How to Use

1. Write HTML in the HTML editor.
2. Write styling in the CSS editor.
3. Write logic in the JavaScript editor.
4. Click the output/run icon.
5. View the rendered result.
6. Use copy icons to copy code from any panel.
7. Use the fullscreen icon to enlarge the output.

---

## 🧠 JavaScript Functionality

The project uses JavaScript to:

```text
✔ Read code from textareas
✔ Insert HTML into an iframe
✔ Insert CSS inside a style element
✔ Execute JavaScript code
✔ Copy editor text to the clipboard
✔ Toggle fullscreen output mode
```

Core rendering logic:

```javascript
output.contentDocument.body.innerHTML = htmlinput.value;
output.contentDocument.head.innerHTML = `<style>${cssinput.value}</style>`;
output.contentWindow.eval(jsinput.value);
```

---

## 💡 What I Learned

While building this project, I practised:

- Selecting DOM elements
- Adding click event listeners
- Reading textarea values
- Updating iframe content
- Executing dynamic JavaScript
- Using the Clipboard API
- Toggling CSS classes
- Structuring a practical web tool
- Working with multiple editor panels
- Managing HTML, CSS and JavaScript together

---

## 📱 Responsive Design

The interface is intended to support:

- Desktop computers
- Laptops
- Tablets
- Smaller screens

The editor and output sections can be adjusted through responsive CSS to provide a better experience across different devices.

---

## 🔮 Future Improvements

- Add automatic live preview while typing
- Add syntax highlighting
- Add line numbers
- Add error messages
- Add console output
- Add reset and clear buttons
- Add download-code functionality
- Add local-storage saving
- Add dark and light themes
- Add starter code templates
- Add keyboard shortcuts
- Add resizable editor panels
- Add HTML, CSS and JavaScript formatting
- Add mobile-layout improvements
- Replace JavaScript `eval()` with a safer execution approach

---

## ⚠️ Security Note

This project executes JavaScript entered by the user inside the browser.

For a personal learning project, this approach is simple and useful. However, directly executing untrusted JavaScript using `eval()` is not suitable for a public multi-user production platform.

A more advanced version should use:

- A sandboxed iframe
- Restricted iframe permissions
- Content Security Policy
- Safer isolated code execution
- Input and output protection

---

## 🏗️ Project Status

```text
Project Type : Frontend Web Application
Status       : Functional
Framework    : None
Backend      : Not Required
Main Focus   : JavaScript and DOM Manipulation
```

---

## 👩‍💻 Developed By

**Rachana Makwana**

MCA Student • Frontend Developer • Cybersecurity Learner

- GitHub: [Rachana0106](https://github.com/Rachana0106)
- LinkedIn: [Rachana Makwana](https://www.linkedin.com/in/rachanamakwana/)
- Portfolio: [Rachana Portfolio](https://rachana0106.github.io/rachana-portfolio/)

---

<div align="center">

### Write. Run. Preview. Learn.

Built with HTML, CSS and JavaScript.

</div>
