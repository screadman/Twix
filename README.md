# Twix

Twix is a fashion storefront (shoes, clothing, accessories) built entirely as a static site with HTML, CSS, and JavaScript, featuring a fully functional shopping cart powered by the browser's sessionStorage; So there's no backend or database involved.

# Academic Context
This project was built for the final course of first-year Computer Science Technology studies at Cégep. The goal was to design a complete, multi-page website that integrates:
- a responsive layout using a CSS framework (Bootstrap)
- consistent navigation across multiple pages,
- client-side JavaScript logic to manage a shopping cart that persists for the duration of the user's session,
- an organized file structure

The chosen theme is a fictional fashion boutique called Twix, with the tagline "Aisance dans l'élégance" ("Ease in elegance").

<h2> Technologies Used</h2>

<table>
  <tr>
    <th>Technology</th>
    <th>Usage</th>
  </tr>
  <tr>
    <td>HTML5</td>
    <td>Semantic page structure</td>
  </tr>
  <tr>
    <td>CSS3</td>
    <td>Custom styling (styles.css, panier.css) and responsive design with media queries</td>
  </tr>
  <tr>
    <td>JavaScript (Vanilla)</td>
    <td>Cart logic, DOM manipulation, and sessionStorage management</td>
  </tr>
  <tr>
    <td>Bootstrap 5.3.2</td>
    <td>Responsive grid system, carousels, navbar, and product cards (via CDN)</td>
  </tr>
  <tr>
    <td>Font Awesome</td>
    <td>Icons for social media, shopping cart, and payment cards (via CDN)</td>
  </tr>
  <tr>
    <td>Google Fonts</td>
    <td>Cormorant Infant typeface for the brand's visual identity</td>
  </tr>
</table>


# Process and learning
- integrating and customizing a CSS framework (Bootstrap) while adding a distinct visual identity,
- structuring a multi-page site with consistent navigation,
- manipulating the DOM in plain JavaScript (creating elements, handling onclick events),
- using the Web Storage API (sessionStorage) as a client-side persistence solution to simulate a shopping cart without a backend,
- handling forms (<select>, radio buttons, number inputs) for product options.



# Known Limitations & Future Improvements
- Hardcoded product IDs (1 to 22) instead of dynamically generated ones. Works fine for a fixed catalog, but doesn't scale well if new products are added.
- Session-only persistence: sessionStorage is cleared when the tab/browser closes (intended for this project, but should be replaced with localStorage or a real database for production use).
- Fixed 10% discount, not configurable, no promo code system.
- No server-side validation of prices/quantities



<img width="2498" height="1326" alt="image" src="https://github.com/user-attachments/assets/999398cb-44a5-45d9-9796-c4d585b58784" />





