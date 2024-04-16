# CSS Advanced

This project focuses on implementing CSS styles for a webpage based on a provided design. Below is a guide on CSS concepts, project requirements, and tasks to accomplish.

## General

### What is CSS?

CSS stands for Cascading Style Sheets. It is a style sheet language used for describing the presentation of a document written in HTML or XML. CSS describes how elements should be displayed on the screen, in print, or spoken.

### How to add style to an element?

Style can be added to an HTML element using CSS by either inline styles, embedded styles, or external style sheets. Inline styles are applied directly to the HTML element using the `style` attribute. Embedded styles are defined within a `<style>` tag in the HTML `<head>`. External style sheets are separate CSS files linked to the HTML document using the `<link>` tag.

### What is a class?

A class is a way to apply a set of styles to one or more HTML elements. Classes are defined in CSS using a dot (`.`) followed by the class name. In HTML, classes are applied to elements using the `class` attribute.

### What is a selector?

A selector is a pattern used to select the elements to which a set of CSS rules will be applied. Selectors can be based on element names, IDs, classes, attributes, and more. For example, `h1` is a selector that targets all `<h1>` elements, while `.btn` targets all elements with the class "btn".

### How to compute CSS Specificity Value?

CSS specificity determines which CSS rule is applied to an element when multiple rules have conflicting styles. Specificity is calculated based on the types of selectors used in a rule. Inline styles have the highest specificity, followed by IDs, classes, and element selectors. Specificity values are typically represented as four numbers: `a, b, c, d`. The higher the number, the higher the specificity. 

### What are Box properties in CSS?

Box properties in CSS control the layout and dimensions of an element's box model. These properties include `width`, `height`, `padding`, `margin`, and `border`. They determine the size, spacing, and positioning of elements on the webpage.

### How does the browser load a webpage?

When a browser loads a webpage, it follows these steps:

1. **Parsing HTML**: The browser retrieves the HTML file and parses it to create the Document Object Model (DOM).
2. **Parsing CSS**: The browser retrieves linked and embedded CSS files and parses them to create the CSS Object Model (CSSOM).
3. **Rendering**: The browser combines the DOM and CSSOM to create the render tree, which is used to render the visual representation of the webpage.
4. **Layout**: The browser calculates the layout of each element on the page, determining their size and position relative to each other.
5. **Painting**: Finally, the browser paints the pixels on the screen according to the layout and styling information.

## Requirements

- All files should end with a new line.
- A `README.md` file at the root of the project folder is mandatory.
- No external libraries are allowed. Use only HTML/CSS/JavaScript.
- Code should be W3C compliant and validate with W3C-Validator.

## Tasks

1. **README and objectives**: Write an amazing README.md and copy the index.html file from the previous HTML project.
2. **Import the style**: Create `styles.css` and import it into `index.html`.
3. **Header and Banner**: Add styling to the header and first section of the page.
4. **Quotes**: Style the quote section.
5. **Videos list**: Apply styling to the videos list section.
6. **Membership**: Add styling to the membership section.
7. **FAQ**: Style the FAQ section.
8. **Footer**: Add styling to the footer.
9. **Make it live!**: Deploy the webpage on Github Pages.

Feel free to refer to the provided Figma design file for styling details and dimensions.

---

## License

This project is licensed under the terms of the MIT license.

## Author

Saima RIAZ

