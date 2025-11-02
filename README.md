# CRUD in JavaScript

A simple client-side CRUD (Create, Read, Update, Delete) project built with plain HTML, CSS and JavaScript. This folder contains a small demo app that demonstrates basic data operations in the browser without a backend.

## Features
- Create new records (items)
- Read and list existing records
- Update records inline or via a form
- Delete records
- Data persisted in browser memory (page refresh clears data) — easily extended to use localStorage or a backend API

## Tech stack
- JavaScript
- HTML
- CSS

## Demo / Preview
Open `index.html` in your browser to run the demo locally. No build tools or server are required for the basic demo.

## Installation / Run locally
1. Clone the repository:
   ```bash
git clone https://github.com/ParmarUday1011/Projects-by-Uday-Parmar.git
   ```
2. Navigate to the project folder:
   ```bash
cd "Projects-by-Uday-Parmar/CRUD in JavaScript"
   ```
3. Open `index.html` in your browser (double-click the file or use a local static server such as `npx http-server`):
   ```bash
npx http-server .
   # then open http://127.0.0.1:8080 (or the address shown)
   ```

## Usage
- Use the form to add a new item.
- Items appear in the list/table where you can edit or delete them.
- Editing an item updates it in the UI; deleting removes it.

## Project structure
- index.html — main HTML file
- styles.css — styles for the demo
- script.js — JavaScript logic for CRUD operations
- assets/ (optional) — images or other static assets

> Note: If your files have different names, update the structure section accordingly.

## Extending / Next steps
- Persist data to localStorage so items survive page refresh.
- Hook up a REST API to persist data on a server.
- Add form validation and better UX.

## Contributing
Contributions are welcome. Open an issue or submit a pull request with improvements.

## License
This project is provided under the MIT License. See LICENSE for details, or add a LICENSE file to the repo.

## Author
ParmarUday1011 — https://github.com/ParmarUday1011
