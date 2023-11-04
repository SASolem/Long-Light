# "Long Light" Landing Page

![Long Light Logo](/Long_LightsCover.jpg)
[Visit My Project on Netlify](https://long-lights.netlify.app/)

Welcome to the "Long Light" landing page. In this document, we'll explain the structure and functionality of the landing page, along with the corresponding CSS and JavaScript.

## Table of Contents
- [HTML Structure](#html-structure)
- [JavaScript Functionality](#javascript-functionality)
- [CSS Styling](#css-styling)

## HTML Structure <a name="html-structure"></a>

The HTML structure of the "Long Light" landing page is organized as follows:

1. **`<head>` Section**: This section contains metadata, including the character set, viewport settings, and a link to an external stylesheet.

2. **`<body>` Section**: The main content of the landing page is within the `<body>` section. Here's what you'll find:

   - **Image Container**: An image of "Long Light" is displayed with a border and centered on the page.

   - **Heading**: The heading "Want to go the extra mile?" is centered on the page.

   - **Philosophy Description**: The landing page features a philosophy description represented by paragraphs. This description expresses "Long Light's" commitment to guiding users towards creativity and innovation.

   - **Get Started Button**: A button with the text "Get Started" is provided to encourage users to take action.

   - **Image Slider Container**: Below the philosophy description, there is an image slider that showcases multiple images. Users can navigate through these images.

   - **Previous and Next Buttons**: These buttons allow users to navigate between the images in the slider.

3. **JavaScript Script**: The JavaScript code for controlling the image slider is included at the end of the HTML document.

## JavaScript Functionality <a name="javascript-functionality"></a>

The JavaScript code in the provided script implements the functionality for the image slider. Here's a summary of its functionality:

- `showSlide(index)`: This function is responsible for showing a specific slide. It takes an index as a parameter and updates the slider to display the corresponding image. If the provided index is out of range, it loops to the beginning or end of the slider.

- `nextSlide()`: This function increments the index to show the next slide. It calls `showSlide` to update the display.

- `prevSlide()`: This function decrements the index to show the previous slide. It also calls `showSlide` to update the display.

- `setInterval(nextSlide, 3000)`: An interval is set to automatically transition to the next slide every 3 seconds (3000 milliseconds).

## CSS Styling <a name="css-styling"></a>

The provided CSS styles are used to style the landing page. Here are some key styles:

- `body`: Sets the background color to a deep blue and text color to white.

- Styles for various elements such as headings, buttons, containers, and images are provided to create a visually appealing and responsive layout.

- Media queries are used to adjust styles for smaller screens (max-width: 600px) to ensure a good user experience on mobile devices.
