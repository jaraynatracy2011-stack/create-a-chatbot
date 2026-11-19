# Contributing

Thanks for your interest in improving Magic 8 Ball Chatbot! This is a small browser-based project built with HTML, CSS, and vanilla JavaScript.

## Getting started

1. Fork the repository and create a branch for your change.
2. Open `index.html` directly in a browser, or start a local server from the repository root:

   ```bash
   python -m http.server 8000
   ```

3. Visit `http://localhost:8000` and test your changes in the browser.

## Making changes

- Keep the app lightweight and dependency-free unless a new dependency is necessary.
- Preserve the existing responsive layout and make interactive controls usable with a keyboard.
- Use semantic HTML and accessible labels or live-region announcements where appropriate.
- Keep user-provided text as text; avoid inserting it as HTML.
- Make changes focused, and update the README when behavior or setup instructions change.

## Before submitting

- Test the app in a modern browser at both desktop and mobile widths.
- Check the browser console for errors.
- Verify the question form, randomized answer, animation, and chat history still work.
- Include a clear description of what changed and how you tested it in your pull request.

## Reporting issues

When opening an issue, describe the steps to reproduce the problem, what you expected to happen, what actually happened, and your browser/device if relevant.
