# Card UI Layout

## Overview

This project is a responsive card-based user interface built using HTML and CSS. It displays multiple cards in a flexible layout, each representing an order summary with pricing details and actions.

The design focuses on simplicity, clean layout, and modern UI styling using gradients, shadows, and hover effects.

## Features

* Responsive flexbox layout
* Reusable card components
* Smooth hover scaling effect
* Gradient background design
* Clean and structured UI
* Integrated icons using Font Awesome

## Project Structure

```
project/
│── index.html
│── style.css
│── Images/
│    └── payment.png
```

## Technologies Used

* HTML5
* CSS3 (Flexbox, Gradients, Shadows)
* Font Awesome (for icons)

## How It Works

* The `.container` uses Flexbox to arrange cards in rows with wrapping.
* Each `.card` represents a single UI block containing:

  * Image
  * Title
  * Description
  * Pricing section
  * Action button
* Hover effect scales the card slightly for better interactivity.
* The layout adjusts automatically based on screen size due to flex-wrap.

## Key Components

### Container

* Full-width layout
* Gradient background
* Centers all cards with spacing

### Card

* Fixed dimensions
* Rounded corners
* Hover animation for interactivity

### Info Section

* Vertically aligned content
* Includes title, description, pricing, and actions

### Price Box

* Displays plan details
* Includes icon and change option
* Styled with subtle background highlight

## Usage

1. Clone or download the project.
2. Open `index.html` in your browser.
3. Ensure the `Images` folder contains the required image file.

## Notes

* The same card structure is reused multiple times to demonstrate layout consistency.
* You can easily customize content by modifying the HTML.
* Styles can be extended for responsiveness or theme variations.

## Reference

The HTML structure used in this project is available here: 

## Author

Rutwik Patil
