# AMAZON_UI_CLONE
AMAZON UI CLONE


# Amazon Clone Project

This project is a frontend clone of Amazon's e-commerce website, built using HTML and CSS. The implementation focuses on recreating Amazon's user interface with responsive design and interactive elements.

## Project Structure

```
amazon-clone/
├── index.html
├── index.css
├── amazon_logo.png
├── hero_image.jpg
└── box1_image.jpg to box16_image.jpg
```

## Technical Implementation Details

### Header Section
- **Navigation Bar (`navbar`)**: 
  - Fixed position at the top with height of 60px
  - Dark background (`#0f1111`) with white text
  - Flex container with evenly spaced elements
  - Interactive hover effects on navigation items with transparent borders

- **Logo**: 
  - Implemented as a background image in a 100px × 50px container
  - Part of the main navigation bar

- **Search Bar**:
  - Custom-styled dropdown with "All" categories
  - Expandable input field with orange search button
  - Hover effect with orange border
  - Total width of 625px with 45px height

- **Secondary Navigation Panel**:
  - 40px height with darker background (`#222f3d`)
  - Contains additional navigation options and deals
  - Flex layout for even spacing

### Hero Section
- Full-width banner with background image
- Height of 350px
- Bottom-aligned message bar with white background
- Custom styling for links with `#007185` color

### Shop Section
- Responsive grid layout using flexbox
- `flex-wrap` enabled for responsive design
- Each product box:
  - 23% width for 4-column layout
  - 400px height
  - White background with padding
  - Consistent image sizing (300px height)
  - "See more" links styled in Amazon blue

### Footer Section
- Four distinct panels with different styling:
  1. Back-to-top button (`foot-panel1`)
  2. Information links section (`foot-panel2`)
  3. Logo section (`foot-panel3`)
  4. Legal information (`foot-panel4`)

- **Link Sections**:
  - Organized in columns using flexbox
  - Consistent spacing with 25px line height
  - Light grey links (`#cfcdcd`) with white headers

## CSS Features

### Key Styling Elements
1. **Reset Styles**:
   - Margin reset to 0
   - Arial font family
   - Border-box sizing

2. **Interactive Elements**:
   - Hover effects on navigation items
   - Interactive search bar with orange highlight
   - Styled links with specific colors for different sections

3. **Layout Techniques**:
   - Extensive use of flexbox for alignment
   - Fixed positioning for navigation
   - Responsive grid using percentage-based widths
   - Background images with cover sizing

### Color Scheme
- Primary Navigation: `#0f1111` (dark gray/black)
- Secondary Navigation: `#222f3d` (darker blue-gray)
- Links: `#007185` (Amazon blue)
- Search Icon: Orange (`rgba(255, 166, 0, 0.932)`)
- Footer: Multiple shades of dark gray
- Text: White and light gray variations

## Responsive Design
- Flexible grid system using percentage-based widths
- Shop section adapts to screen size with `flex-wrap`
- Fixed navigation bar for consistent user experience
- Scalable image containers with background-size: cover

## Usage Instructions
1. Clone the repository
2. Ensure all images are in the correct directory structure:
   - `amazon_logo.png` for the logo
   - `hero_image.jpg` for the banner
   - `box1_image.jpg` through `box16_image.jpg` for product images
3. Open `index.html` in a web browser

## Development Notes
- The project uses pure HTML and CSS without any JavaScript
- All interactive elements are achieved using CSS hover states
- Images are implemented as background images for consistent scaling
- The layout is optimized for desktop viewing
