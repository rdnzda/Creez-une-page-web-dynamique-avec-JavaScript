# Sophie Bluel – architect portfolio (dynamic page with JavaScript)

**OpenClassrooms "Web Integrator" program – project 6.**

The front end of a portfolio website for an interior architect (a fictional case study), made dynamic with vanilla JavaScript and connected to a provided REST API.

## Features

- Project gallery loaded from the API with `fetch`
- Category filters generated from the API data
- Login page that sends the credentials to the API and stores the returned token
- Edit mode for the logged-in user, with a modal to:
  - delete a project (authenticated `DELETE` request)
  - add a project with an image upload (`FormData` sent with a `POST` request)
- Logout that clears the stored session

## Tech stack

- HTML5, CSS3
- Vanilla JavaScript (DOM manipulation, `fetch`, `async`/`await`)
- REST API provided by OpenClassrooms (Node.js back end, not included in this repository)

## Getting started

1. Start the back end provided by OpenClassrooms (it runs on `http://localhost:5678`).
2. Open `FrontEnd/index.html` in a browser, ideally with a local server such as VS Code Live Server.

## Project structure

```text
FrontEnd/
  index.html     gallery and edit mode
  login.html     login page
  js/main.js     gallery, filters, edit mode and modal
  js/login.js    authentication
  assets/        styles, icons and images
```

---

Training project; the architect is a case study created by OpenClassrooms. Project updated after the final assessment.
