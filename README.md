# mtm6201_final
# Plant Palette Website

## Overview
This is the final project for MTM6201, a responsive website for **Plant Palette**, a restaurant specializing in plant-based cuisine. The site includes three pages: Home, Menu, and Contact, built using HTML, CSS, Bootstrap, and Hover.css. It showcases a clean, accessible, and visually appealing design optimized for various screen sizes, reflecting the restaurant’s vibrant and eco-friendly brand.

## Process
1. **Planning**:
   - Utilized the high-fidelity wireframe from the User Experience I course as a guide to structure the website.
   - Planned three pages: Home (featuring a hero section and highlighted dishes), Menu (showcasing the restaurant’s offerings), and Contact (providing restaurant details and a F&Q).
   - Selected a color scheme (Primary-1: #A1D6A5, Primary-2: #2E3D49, Primary-3: #3F5246, Secondary-1: #F9F9F9, Secondary-2: #5A6D7B) and fonts (Playfair Display, Lora, Montserrat, Open Sans) to align with the restaurant’s fresh and modern aesthetic.

2. **Development**:
   - Created a project folder (`mtm6201_final`) containing HTML files (`index.html`, `menu.html`, `contact.html`), a CSS file (`css/styles.css`), and an `images/` folder.
   - Integrated **Bootstrap 5.3.2** for responsive layouts, leveraging its navbar, grid system, and form components to ensure a seamless user experience across devices.
   - Used **Hover.css** for button hover effects, applying the `hvr-grow` class to enhance interactivity.
   - Applied **Google Fonts**: Playfair Display for primary headings, Lora for section headings, Montserrat for content headings, and Open Sans for body text, buttons, and links.
   - Defined CSS variables (e.g., `--primary-1: #A1D6A5`) to customize Bootstrap’s default color scheme, ensuring brand consistency.
   - Implemented the `<picture>` tag with `srcset` to serve large and small versions of images for optimal performance.
   - Added accessibility features, including semantic HTML, ARIA roles (e.g., `aria-current` for active navigation links), skip links, alt text for images, and keyboard navigation support.
   - Incorporated stock images from Unsplash and Pinterest (listed below) to visually represent the restaurant’s ambiance and menu items.

3. **Deployment**:
   - Published the site to GitHub Pages, accessible at `https://github.com/riyansidonga/mtm6201_final.git`.
   - Tested the live site to confirm all assets loaded correctly and the design was responsive.

## Challenges and Solutions
- **Challenge**: Balancing Bootstrap’s default styles with the custom design requirements.
  - **Solution**: Used CSS variables and targeted selectors to override Bootstrap’s defaults (e.g., setting `--primary-1` for buttons and headings) without disrupting its responsive features.
- **Challenge**: Optimizing images for performance while maintaining quality.
  - **Solution**: Created large and small versions of each image, using the `<picture>` tag with `srcset` and media queries to deliver the appropriate size based on device.But some images are not in good quality.
- **Challenge**: - I found it challenging to create the main menu for the menu page, especially organizing the layout and making it visually clear and functional.

## Lessons Learned
- **Bootstrap Customization**: Learned to efficiently override Bootstrap’s default styles using CSS variables and specific selectors, maintaining its responsive functionality.
- **Accessibility**: Deepened understanding of ARIA roles, semantic markup, and keyboard navigation, ensuring the site is inclusive for all users.
- **Responsive Images**: Mastered the `<picture>` tag and `srcset` to optimize image delivery, improving site performance across devices.
- **Project Management**: Enhanced skills in organizing project files, adhering to naming conventions (lowercase, no spaces), and documenting the development process clearly.
- **Visual Design**: Gained experience in selecting and integrating stock images to reinforce a brand’s theme, balancing aesthetics with functionality.

## Resources Used
- **Frameworks/Libraries**:
  - [Bootstrap 5.3.2](https://getbootstrap.com/) - Provided responsive layout, navigation, grid system, and form components.
  - [Hover.css 2.3.2](https://ianlunn.github.io/Hover/) - Enabled button hover effects (e.g., `hvr-grow`).

- **Fonts**:
  - [Google Fonts](https://fonts.google.com/):
    - Playfair Display (Bold) - Used for primary headings.
    - Lora (Semibold) - Used for section headings.
    - Montserrat (Bold) - Used for content headings.
    - Open Sans (Regular) - Used for body text, buttons, and links.

- **Images**:
  - All images were sourced from Unsplash and Pinterest with appropriate usage rights. They were optimized into large and small versions for responsiveness. The images used are:
    - [Brown wooden table and chairs](https://unsplash.com/photos/brown-wooden-table-and-chairs-WItC-f-K2Ho) - Home Page Hero banner (Unsplash, WItC-f-K2Ho).
    - [Green and red flower painting](https://unsplash.com/photos/green-and-red-flower-painting-sefKM7XR56I) - Home page Banner (Unsplash, sefKM7XR56I).
    - [White ceramic bowl on plate](https://unsplash.com/photos/white-ceramic-bowl-on-white-ceramic-plate-ou_7_3e-AqU) - Menu page banner (Unsplash, ou_7_3e-AqU).
    - [Soup with green leaf](https://unsplash.com/photos/soup-with-green-leaf-on-white-ceramic-bowl-18YZ7zuQG4Q) - Menu page soup (Unsplash, 18YZ7zuQG4Q).
    - [Fruits and vegetables on chopping board](https://unsplash.com/photos/assorted-fruits-and-vegetable-on-brown-wooden-chopping-board-2IxTgsgFi-s) - Menu page sandwich (Unsplash, 2IxTgsgFi-s).
    - [Plant-themed illustration](https://ca.pinterest.com/pin/4222193394768390/) - Home page Special (Pinterest, Pin 4222193394768390).
    - [Green plant pot](https://ca.pinterest.com/pin/144959681750077450/) - Home page Special moose (Pinterest, Pin 144959681750077450).
    - [Plant in pot](https://tr.pinterest.com/pin/780530179153451659/) - Contact page F&Q (Pinterest, Pin 780530179153451659).
    - [Minimalist plant decor](https://tr.pinterest.com/pin/11399805458184880/) - Contact page Dining (Pinterest, Pin 11399805458184880).
    - [Green leafy plant](https://tr.pinterest.com/pin/377950593743728843/) - Contact page Dining (Pinterest, Pin 377950593743728843).
    - [Decorative plant arrangement](https://in.pinterest.com/pin/648729521295183221/) - Contact page Location (Pinterest, Pin 648729521295183221).

## Assets
- **Mockup**: Stored in `images/mockup.jpg`.
- **Images**: 
  - Logo (`logo-large.png`, `logo-small.png`)
  - Hero (`hero-large.jpg`, `hero-small.jpg`) - Uses the Unsplash wooden table image.
  - Menu items and decor - Sourced from the listed Unsplash and Pinterest images, optimized for web use.

## Deployment
The site is hosted on GitHub Pages and can be accessed at `https://riyansidonga.github.io/mtm6201_final/index`

**Created by Riyansi Donga for MTM6201, April 2025.**