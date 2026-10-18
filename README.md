# AntiGravity AI Debugging Tutor 🚀

> **An interactive AI mentorship & code diagnostics web application designed for first-year BCA (Bachelor of Computer Applications) students learning Python & C programming.**

![BCA Semester 1 & 2](https://img.shields.io/badge/Curriculum-BCA%20Sem%201%20%26%202-6366f1?style=for-the-badge)
![Languages](https://img.shields.io/badge/Languages-Python%20%7C%20C-10b981?style=for-the-badge)
![UI](https://img.shields.io/badge/Theme-Modern%20Dark%20Slate-06b6d4?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Complete-success?style=for-the-badge)

---

## 👥 Project Team & Engineering Credits

Designed and developed by:
* **Nupur Vaishnav**
* **Shambhavi Kekre**
* **Raj Prajapat**
* **Mahi Mali**

---

## ✨ Key Features

1. **Modern Dark UI & Developer Aesthetic:**
   - Dark slate background (`#070b14`) with glowing neon accents (Emerald, Cyan, and Purple).
   - Monospaced code fonts (`Fira Code`, `JetBrains Mono`) for readability.
   - Built-in **Viva & Error Guide** covering Syntax vs Runtime vs Logical Errors and classic BCA lab viva questions.

2. **Code Input & Analysis Workspace:**
   - Multi-line code editor with a synchronized line numbers gutter.
   - 4-space Tab indentation and line/character metrics.
   - Dual-language support toggle: 🐍 **Python** and ⚙️ **C**.
   - Glowing **"Debug Code with AI"** button with dynamic radar scanning feedback.

3. **3-Step Diagnostic Engine:**
   - **Step 1: Plain Language Explanation:** Friendly, non-intimidating mentorship tone with everyday analogies + BCA Exam Viva Tips.
   - **Step 2: Exact Location & Fixed Code:** Pinpoints the exact line number, explains the root cause, and provides the corrected code block with a one-click **"Copy Code"** button.
   - **Step 3: Test Cases Suite:** 2 distinct test cases (Standard Normal Input + Edge-Case Boundary) proving why the fix works, plus an interactive **Output Simulator**.

4. **1-Click Pre-Loaded Preset Error Scenarios:**
   - ⚡ **Preset 1 (Python Syntax Error):** Missing colon in if-statement (`if age >= 18`).
   - ⚡ **Preset 2 (Python Type Error):** Concatenating string and integer (`"I am " + age + " years old."`).
   - ⚡ **Preset 3 (C Logic Error):** Uninitialized accumulator variable holding garbage memory (`int sum;` in array loop).

5. **Custom Error Analyzer Fallback Logic:**
   - Custom client-side parsing for user-pasted code covering missing colons, missing semicolons, string-int concatenation, uninitialized variables, division by zero, `scanf` without `&`, and unbalanced brackets.

---

## 🚀 How to Run Locally

No installations or local servers required!

1. Download or clone this repository.
2. Double-click **`index.html`** to open it in any modern web browser (Google Chrome, Microsoft Edge, Firefox, Brave, Safari).

---

## 🌐 Deploying to GitHub Pages (Live Website)

You can host this project as a live website for free on GitHub Pages:
1. Push this repository to GitHub.
2. Go to your repository's **Settings** tab.
3. In the left sidebar, click **Pages**.
4. Under **Branch**, select `main` (or `master`) and folder `/ (root)`.
5. Click **Save**. Within 1–2 minutes, your web application will be live at:
   ```
   https://<your-username>.github.io/<repository-name>/
   ```
