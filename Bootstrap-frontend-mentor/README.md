# Frontend Mentor – QR Code Component

## Overview
This project is an implementation of the Frontend Mentor **QR Code Component** challenge using Bootstrap. The goal was to accurately recreate the provided Figma design while ensuring responsiveness.

**Challenge Link:** https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H

## Approach
I used Bootstrap’s grid system to center the content and Bootstrap’s card component for structure. Utility classes were used for spacing and typography, with minimal custom CSS added to match the design.

## Challenges
One challenge was matching the spacing and proportions of the design. I addressed this by adjusting Bootstrap utility classes and testing the layout across different screen sizes.

## Improvements
With more time, I would further refine spacing details and test across additional devices and browsers.

## Reflection
During this project, one of the main challenges I encountered was getting the card layout to appear perfectly centered on the page. At first, it looked off to the left, which was confusing because I thought I had followed the Bootstrap grid system correctly. After reviewing the container and flex classes, I realized that the .row element was creating extra margins that shifted the content. Removing the row and using a single column inside a flex-centered container solved the issue and made the design look aligned with the Figma reference.

Another challenge was making sure the QR code image itself was centered within the card. Using Bootstrap’s mx-auto and d-block classes fixed this quickly, and I learned how useful small utility classes can be for adjusting layout without writing extra CSS.

If I had more time, I would refine spacing and test on more devices to ensure pixel-perfect responsiveness. Overall, this assignment strengthened my understanding of Bootstrap’s grid, flex utilities, and how to structure projects for Git and GitHub.