# Test-case-for-Product-Display
# Product Display Test Case
## Overview
This repository contains test cases for validating the functionality of a product display feature in a web or mobile application. The purpose is to ensure that products are displayed correctly,consistently, and as per the specified requirements.
## Features Tested
- Correct display of product information (name, price, image, etc.)
- Responsiveness and layout on different screen sizes
- Functionality of interactive elements (e.g., add to cart, wishlist buttons)
- Loading performance and placeholder handling
- Accessibility compliance (e.g., screen reader support)
#### Accessibility Tests
Use tools like Axe or Lighthouse directly within your browser or integrate them into your CI/CD pipeline.
### Functional Test Case: Display Correct Product
- **Description**: Verify that the correct product details (name, price, image, etc.) are displayed when a product is selected.
- **Steps**:
  1. Navigate to the product listing page.
  2. Click on a product.
  3. Verify the product details on the product details page.
- **Expected Result**: Product details match the selected product.
- ### Performance Test Case: Page Load Time
- **Description**: Ensure that the product display page loads within acceptable limits.
- **Steps**:
  1. Measure the time taken to load the product display page.
- **Expected Result**: Page load time is less than 2 seconds.
