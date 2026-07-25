# Portfolio Website

A single-page personal portfolio website, built with plain HTML and inline CSS.

## Overview

This is a self-contained `index.html` file that presents an introduction, an about section, a skills list, featured projects, and a contact form. No build step or external dependencies are required.

## Sections

- **Banner**: Name, profile photo, and a short introduction, with a link to GitHub.
- **About Me**: Academic background as a Computer Science and Engineering student at International Islamic University Chittagong, with an interest in software development, AI, and data science, and an aspiration toward an academic career.
- **Skills**: Programming languages (Python, C++, C#, JavaScript, HTML/CSS, SQL), web development (React.js, Node.js, Bootstrap), version control (GitHub), database management (MySQL, MongoDB), and tooling (VS Code).
- **Portfolio**: Featured projects:
  - **Journey Planner**: a console-based C++ application implementing Dijkstra's Algorithm and DFS for route planning over a graph-modeled map.
  - **Blood Donation System**: a full-stack web app (HTML, CSS, JavaScript, PHP, MySQL) connecting blood donors with recipients.
- **Contact**: A contact form (name, email, message) plus direct email and phone details.

## Structure

| File | Description |
|---|---|
| `index.html` | The entire site: markup, styling, and content in one file. |

## Usage

Open `index.html` directly in a browser, or serve it with any static file server:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Notes

The contact form is currently front-end only. Submitting it does not send an email or persist data. Wiring it to a backend or a form service, such as Formspree, would be needed for it to function.

## License

Not currently specified.
