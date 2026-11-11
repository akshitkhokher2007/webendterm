# QONYS Apartment Renting Website

**Topic:** Apartment renting (sample listings in Almaty and Astana)
**Author:** Akshit Khokher (individual project)

## Short description

QONYS is a responsive website for exploring sample rental apartments in Almaty and Astana. It has five pages: Home, Apartments, Prices, About Us and Contact. The endterm version extends the midterm website with JavaScript and jQuery interactivity: form validation, live search and filters, a price table with full CRUD, and a photo gallery with a lightbox. All midterm HTML, CSS and responsive layouts remain intact.

## Author and individual contribution

This project was originally started as a group project. For the endterm it was completed individually by **Akshit Khokher**, who is responsible for all of the work:

| Area | Contribution by Akshit Khokher |
| --- | --- |
| Home, Apartments, Prices, About Us and Contact pages | Built and maintained the HTML structure and content of all five pages. |
| `css/style.css` | Wrote the custom styles and the responsive layouts, on top of Bootstrap. |
| Form validation (Contact) | Built the renter registration form with RegEx email check, password strength bar, password confirmation and live feedback. |
| Search and filter (Apartments) | Implemented the live case-insensitive search and the city filter buttons. |
| Dynamic table with CRUD (Prices) | Implemented adding, editing and deleting price records with a confirmation prompt. |
| Image gallery and lightbox (Apartments) | Built the photo grid and the jQuery fade lightbox with navigation arrows. |
| Documentation and deployment | Wrote this README and published the website. |

## Features implemented

- **Registration form validation (Contact):** required checks for name, email, password and message; email format checked with a regular expression; a coloured password strength bar with a Weak, Medium or Strong label; a password confirmation check; real-time feedback with success and error icons and text messages. Invalid entries block submission and show guidance. A valid submission shows a success message.
- **Dynamic search and filter (Apartments):** a case-insensitive live search by apartment name, city or district using jQuery `.on("input keyup")`. The All, Almaty and Astana buttons work independently or together with the search, with no page reload.
- **Dynamic table with CRUD (Prices):** prices are rendered from JavaScript data. **Add** through the form, **Read** in a formatted table, **Update** with the Edit button, and **Delete** with a confirmation prompt. Changes are saved in the browser with local storage.
- **Image gallery (Apartments):** a responsive Bootstrap photo grid. Clicking a photo opens a lightbox with previous and next arrows (keyboard arrows and Escape also work). The lightbox fades in and out with jQuery `.fadeIn()` and `.fadeOut()`.

## Technologies used

- HTML5 and CSS3 (custom responsive styles in `css/style.css`)
- Bootstrap 5.3.3 (grid, forms, buttons, progress bar, alerts), included locally
- JavaScript in `js/script.js`
- jQuery 3.7.1 in `js/jquery.min.js`

## Run the project

Open `index.html` in a browser, or serve the folder with VS Code Live Server. To try the endterm features open Apartments (search, filters, gallery), Prices (CRUD table) and Contact (registration form). The website uses demo listings and everything runs in the browser.

## Project links

- Published website: **ADD YOUR GITHUB PAGES / NETLIFY LINK HERE**
- GitHub repository: **(https://github.com/akshitkhokher2007/webendterm.git)**

## Content and image credits

The apartment names, rents and contact details are examples. The photos illustrate interiors. The midterm template credits Clay Banks on Unsplash, Curtis Adams on Pexels and Furkan Tumer on Pexels.
