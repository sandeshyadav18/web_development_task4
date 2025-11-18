## Objective
Convert a desktop-only webpage into a mobile-friendly responsive website using CSS media queries.

## Tools Used
HTML
CSS
VS Code

## Chrome DevTools (Device Toolbar)
## Features
*Desktop View
Horizontal navigation bar
Two boxes side-by-side
Large hero section
Wider layout for big screens

*Mobile View (Below 768px)
Navbar becomes vertical
Menu links stack vertically
Boxes become full-width
Font size reduces
Layout adapts to small screens
Images scale automatically

## How It Works

Responsive styles are added using a media query:
@media (max-width: 768px) {
  /* mobile styles here */
}
Inside this media query:
Columns stack vertically
Font sizes shrink
Containers become full width
Navigation becomes vertical

## How to Test Mobile View
Open the webpage in Google Chrome
Right-click → Inspect
Click Toggle Device Toolbar (phone icon)
Choose a device like iPhone 12
The responsive layout will appear

## Final Output
Desktop view shows a wide layout
Mobile view becomes compact and vertical
Fully responsive using only CSS
