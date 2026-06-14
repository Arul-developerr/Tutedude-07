This project is a fully responsive landing page for a laundry service application. This specific version focuses on the **Mobile View Implementation**, successfully completing the assignment requirements to build an interactive mobile navigation system entirely without JavaScript.

## Mobile View Features
- **CSS-Only Hamburger Menu:** Features a fully functional side-navigation menu that slides in from the right when the hamburger icon is clicked.
- **Zero JavaScript:** The mobile menu toggle is built purely with CSS, utilizing the `<button>` `:focus` pseudo-class combined with the adjacent sibling combinator (`+`).
- **Responsive Hero Section:** In mobile view (screens under 600px), the layout elegantly shifts from a side-by-side flex row to a stacked, centered column layout for optimal readability.
- **Hidden Desktop Links:** Standard navigation links are hidden on mobile devices to save screen space, replaced by the hamburger toggle.

## How the CSS Menu Trick Works
As per the assignment requirements, the menu does not use JavaScript to track clicks. Instead:
1. The hamburger icon is wrapped in a `<button>` element.
2. The hidden `.side-menu` is placed immediately after the button in the HTML structure (making them siblings).
3. We use the CSS rule `.nav-btn:focus + .side-menu { display: block; }`. When the user taps the button, it enters a "focused" state, which triggers the CSS to reveal the adjacent side menu.


## Files Included
1. `index.html`: The main HTML structure of the page.
2. `style.css`: All the styling rules, including standard styles and  `@media` queries for responsiveness.
4. `Readme.md`: Project documentation.
5. Image assets (Logo and Hero illustration).

## How to Run
1. Extract the `.zip` folder.
2. Ensure `index.html`, `style.css`, and your `image/` folder (containing `logo.png` and `a.jpeg`) are in the exact same directory.
3. Double-click `index.html` to open it in any modern web browser (Chrome, Firefox, Safari, Edge). No local server is required.

