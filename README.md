# Image-gallery

![Screenshot_1](https://github.com/Cosaslearning/Image-gallery/assets/100014446/28a6f0ed-a582-4ff8-85c4-fb9477dacc83)

This code represents a simple image gallery web application. Users can view images in a gallery by rotating them in a 3D space. The code includes an HTML file, a CSS file, and a JavaScript file. Below is an explanation of each part:

**HTML File (index.html):**

- The HTML file defines the structure of the web page, including the use of Font Awesome icons for arrows and references to external CSS and JavaScript files.
- It contains a container with a header, logo, and the main content section.
- The main content section includes an image gallery with multiple images enclosed in `span` elements. These images can be rotated in a 3D space.
- Additionally, there are buttons for navigating the gallery.

**CSS File (style.css):**

- The CSS file defines the styling for various elements in the HTML, such as the container, header, logo, hero section, and navigation buttons.
- It uses CSS variables for colors, and it sets up styles to create a visually appealing gallery.

**JavaScript File (script.js):**

- The JavaScript file is responsible for the functionality of the image gallery.
- It selects elements from the HTML using `document.querySelector()` and `document.querySelectorAll()`.
- It sets up a degree variable (`deg`) to track the rotation of the gallery.
- It calculates the rotation angle for each image and applies it to create a 3D gallery.
- It adds event listeners to the previous and next buttons, allowing users to navigate the gallery by changing the rotation angle (`deg`).

This code creates a visually appealing 3D image gallery with rotating images and navigation buttons. Users can interact with the gallery to view the images in a unique way. The CSS and JavaScript work together to achieve this effect. You can further customize this gallery by adding more images or modifying the styles.
