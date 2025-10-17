# Simple Math Quiz

## Overview
A minimal single‑page web application that asks the user a basic arithmetic question. It demonstrates interactive UI handling with vanilla JavaScript and styling with **Bootstrap 5**.

## Features
- Displays the question **“What is 2 + 2?”**.
- Four answer buttons (3, 4, 5, 6) styled with Bootstrap.
- Immediate feedback:
  - **Correct!** shown in green when the right answer (4) is selected.
  - **Try again!** shown in red for any wrong answer.
- Fully responsive layout using Bootstrap’s grid utilities.

## How to Use
1. Open `index.html` in any modern web browser.
2. Click one of the answer buttons.
3. Observe the feedback message appear below the buttons.

No build steps or server are required; everything runs client‑side.

## Technical Details
- **HTML5** – single file containing markup, inline CSS, and JavaScript.
- **Bootstrap 5** – loaded via CDN for styling and responsive layout.
- **Vanilla JavaScript** – adds click listeners to the answer buttons, evaluates the answer, and updates the result `<div>` with appropriate text and color classes (`text-success` / `text-danger`).

### File Structure
```
index.html   ← all code (HTML, CSS, JS) in one file
README.md    ← this documentation
```

## License
This project is licensed under the **MIT License**.

```
MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS
IN THE SOFTWARE.
```