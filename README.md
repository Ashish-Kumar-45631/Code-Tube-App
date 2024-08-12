# Project Description: CodeTube Catalog

## Overview
CodeTube Catalog is an online platform designed for purchasing courses and following favorite instructors. It provides users with a seamless experience to browse, select, and buy courses from various categories while allowing them to follow and keep track of their preferred instructors.

## Key Features

- **Course Browsing and Purchase:** 
  - Users can explore a wide range of courses, view detailed information, and purchase them directly through the platform.

- **Instructor Follow/Unfollow:** 
  - Users can follow their favorite instructors to stay updated with new course offerings and unfollow them at any time.

- **Reusable Components:** 
  - The platform leverages styled-components to create reusable UI elements. Key components include:
    - **Button Component:** 
      - A customizable button that adapts based on the `bg` (background color) prop passed to it. This component is used across the platform, including in the `Course.js` and `Sidebar.js` files.
    - **Container Component:** 
      - A flexible container component that adjusts its layout based on the `flex` prop. It is used to enclose courses and instructor lists in the `List.js` and `Sidebar.js` files.

- **Dynamic Updates:**
  - The "Add to Bag" button allows users to add courses to their shopping bag, with the item count dynamically updating on the navbar.
  - The "Follow" button lets users follow instructors, reflecting real-time updates in the UI.

## Testing

- Ensure that data, including courses and instructors, is rendered correctly.
- Validate that button interactions, such as "Add to Bag" and "Follow," work as expected, with the correct updates in the UI.
- Verify that the styled components' properties are applied correctly according to the passed props.
