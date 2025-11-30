# 🌐 HW - Routing

A Node.js web server that implements routing to serve multiple HTML pages and external CSS.

## 📋 Task Requirements

1. Create a project folder.
2. Create a `templates` sub-folder within the project folder.
3. Create a `page.html` file that looks like the attached image. You can use a different image.
4. **Mandatory** to use external CSS, place the file in the appropriate folder.
5. Create an `app.js` file that creates a server sending the files to the FrontEnd.
6. Create "About" and "Contact Us" pages (free content and design).
7. Add them to the previous project.
8. Add a navigation menu to navigate between these pages.

## 🚀 How to Run

```bash
node app.js
```
Then open your browser at `http://localhost:3000`

## 💡 Solution Approach

The solution uses:
- `http` module to create a web server
- `url` module to parse request URLs
- `fs` module to read files (HTML, CSS)
- Routing logic to serve different pages (`/`, `/about.html`, `/contact.html`)
- Serves external CSS files

## 👥 Students

- Bshara Karkaby [49-2]
- Moner Makhouly [49-2]

---

**Happy coding!** 💻✨
