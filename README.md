# Product Preview Card Component

A responsive product preview card for **Gabrielle Essence Eau de Parfum**, built with HTML and Tailwind CSS. This project focuses on translating a visual design into a clean, accessible interface that adapts to mobile and desktop screens.

## Preview

**Live Demo:** [View the deployed website](https://6ad0c2afd6510a13325a1641--lovely-marzipan-faaced.netlify.app/)

**Source Code:** [View the GitHub repository](https://github.com/yasmin3802/product-preview-card-component)

### Desktop
![Desktop view of the Gabrielle Essence product preview card with the image on the left and product details on the right](./screenshots/desktop.png)

### Mobile
![Mobile view of the product preview card with the image stacked above the product details](./screenshots/mobile.png)

## Project Overview

The component presents a perfume product with its image, category, title, description, discounted price, original price, and an Add to Cart button.

The main goal was to recreate the reference design while maintaining a responsive layout, clear visual hierarchy, and accessible interactions.

## Features

- **Responsive layout:** The product image and information rearrange for smaller and larger screens.
- **Responsive imagery:** Uses the appropriate product image for mobile and desktop viewports.
- **Clear visual hierarchy:** Typography, spacing, and color distinguish the product details and pricing.
- **Interactive button states:** Hover, keyboard-focus, and active states provide visual feedback.
- **Semantic HTML:** Uses meaningful page structure and descriptive alternative text for the product image.

## Built With

- HTML5
- Tailwind CSS
- Vite for local development and production builds
- Git and GitHub for version control
- Netlify for deployment

## Implementation Notes

### Responsive layout

Tailwind CSS utility classes control the card's layout, spacing, typography, colors, and alignment. A responsive grid allows the product image and details to appear side by side on larger screens while adapting to a compact mobile layout.

### Accessibility and interaction

The product image includes descriptive alternative text, and the Add to Cart button has visible interaction states. Keyboard-focus styling helps users identify the currently focused control.

## What I Learned

This project helped me practice turning a visual reference into a working interface using utility-first CSS.

In particular, I worked on:

- Applying responsive layout utilities and breakpoint-based styling.
- Using spacing, typography, and color to create a consistent visual hierarchy.
- Adding hover and keyboard-focus styles to interactive elements.
- Using Git and GitHub to manage source code and Netlify to publish a website.

## Challenges and Problem-Solving

One of the main challenges was refining the spacing, typography, and proportions so the component felt closer to the reference design across different screen sizes. I used Tailwind CSS classes to adjust the layout and styling rather than relying on a large collection of custom CSS rules.

I also encountered Git setup difficulties during submission. Resolving them gave me practical experience with repository configuration and the importance of keeping generated files and installed dependencies out of source control when they are not needed in the repository.

## Running Locally

To run the project locally, first make sure Node.js and npm are installed.

1. Clone the repository:

   ```bash
   git clone https://github.com/yasmin3802/product-preview-card-component.git
   ```

2. Navigate into the project directory:

   ```bash
   cd product-preview-card-component
   ```

3. Install the project dependencies:

   ```bash
   npm install
   ```

4. Start the development server:

   ```bash
   npm run dev
   ```

   Open the local URL displayed in your terminal.

To create a production build, run:

```bash
npm run build
```

*These commands assume the repository contains a `package.json` with the `dev` and `build` scripts shown above.*

## Future Improvements

- Compare the finished page more closely against the reference at mobile and desktop sizes.
- Continue improving accessibility and responsive behavior.
- Refine HTML structure and styling for easier maintenance.
- Build a more consistent workflow for commits, testing, and deployment.

## Acknowledgments

Challenge and design reference provided by [Frontend Mentor](https://www.frontendmentor.io/).
