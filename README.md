# Mo-mano.github.io

# My Personal Portfolio

## Overview

This portfolio page showcases my software development projects and skills. It is built using standard web technologies and demonstrates proficiency in dynamic DOM manipulation, data storage (Session and Local Storage), and responsive design.

### Languages and Libraries Used

- **HTML5:** Used for the semantic structure of the page (sections, headers, navigation).
- **CSS3:** Used for styling, including Flexbox for layouts, CSS Variables, and a Dark Mode toggle.
- **JavaScript (ES6):**
  - **DOM Manipulation:** Dynamically creating project cards, skills lists, and updating text content using `document.createElement`.
  - **JSON & Storage:** Using `JSON.stringify()` and `JSON.parse()` to handle project objects stored in `sessionStorage` for persistence across page reloads.
  - **Event Listeners:** Handling form submissions and user interactions.

### Dependencies

- **None:** This project uses vanilla HTML, CSS, and JavaScript. No external libraries (like Bootstrap or jQuery) are required.
- **Images:** Project thumbnails use placeholders from `placehold.co` for demonstration purposes.

### How to Run

1.  Download the `index.html` file.
2.  Open the file in any modern web browser (Chrome, Firefox, Edge).
3.  **Verify Storage:** Open Developer Tools (F12) -> Application -> Session Storage to see the `myProjects` key storing the JSON string.
