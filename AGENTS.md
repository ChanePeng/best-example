## Cursor Cloud specific instructions

This is a minimal static HTML/JS project with no dependencies, no build system, no package manager, and no automated tests.

### Running the site

Serve the project root with any static HTTP server. Example:

```
python3 -m http.server 8080
```

Then open `http://localhost:8080/` in a browser. The page should display the heading **"The Best Cod3z!"** and the JavaScript-generated text **"The script ran!"**.

### Notes

- There is no `package.json`, no linter, no test framework, and no build step.
- The only files that matter are `index.html` and `js/script.js`.
