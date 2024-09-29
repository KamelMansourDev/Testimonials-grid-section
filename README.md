# Testimonials Grid Section - Frontend Mentor

## Overview

This project is a responsive **Testimonials Grid Section**, built using **HTML** and **CSS**. The design uses a grid layout to display multiple testimonial cards in a clean and aesthetically pleasing format. The project adapts to different screen sizes through media queries to ensure an optimal user experience on various devices.

## Technologies Used

- HTML
- CSS
- Google Fonts (Barlow Semi Condensed)

## Features

- **Grid Layout**: The layout is built using CSS Grid, ensuring a flexible and responsive design.
- **Responsive Design**: The layout adapts to different screen sizes using media queries for widths of 1200px, 992px, 768px, and 576px.
- **Custom Colors**: The design uses custom colors stored as CSS variables, making it easy to maintain and update.
- **Typography**: The font used is **Barlow Semi Condensed** from Google Fonts, providing a modern and professional look.
- **Shadow Effects**: Some cards have shadow effects for a slight elevation, adding depth to the design.

## CSS Variables

The following color variables are defined in the `:root` for ease of use:

- `--Moderateviolet`: hsl(263, 55%, 52%)
- `--Verydarkgrayishblue`: hsl(217, 19%, 35%)
- `--Verydarkblackishblue`: hsl(219, 29%, 14%)
- `--White`: hsl(0, 0%, 100%)
- `--Lightgray`: hsl(0, 0%, 81%)
- `--Lightgrayishblue`: hsl(210, 46%, 95%)

## Media Queries

The design includes multiple breakpoints to ensure a responsive layout:

- **1200px**: The grid layout switches to 3 columns.
- **992px**: The grid layout switches to 2 columns.
- **768px**: The grid layout switches to 1 column.
- **576px**: Minor adjustments are made to the font size and padding.

## How to Use

1. Clone the repository or download the project files.
2. Link the provided CSS file in your HTML file.
3. Open the `index.html` file in your browser to view the testimonials grid section.

## Future Enhancements

- Adding animations for smooth transitions between breakpoints.
- Integrating the testimonials with a backend to dynamically load content.
