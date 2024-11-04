# Sign-up Form - The Odin Project

This project is part of [The Odin Project](https://www.theodinproject.com/) curriculum, specifically from the "Project: Sign-up Form" assignment. The primary goal is to design and implement a user-friendly sign-up form, applying skills learned in HTML and CSS, including form validation.

## Project Overview

The **Sign-up Form** page simulates a real estate company named "Real State Solutions" offering prospective homeowners the opportunity to get closer to their dreams. This form layout is designed to be visually appealing, intuitive, and responsive, encouraging users to fill in their information with confidence. 

### Features
- **Left Side (Static Content)**:
  - **Logo Display**: Displays the company logo and name.
  - **Background Image**: A full-height, aesthetic image on the left side of the page.
  - **Footer**: Contains copyright information.

- **Right Side (Form and Text)**:
  - **Quote Block**: Engaging text to encourage user sign-up.
  - **Sign-up Form**: Collects user's first name, last name, email, phone number, and password with various validations.
  - **Create Account Button**: Prompts form submission.
  - **Login Link**: Directs users with an account to log in.

### Validations
- **Name** fields: Text inputs with placeholders for easy understanding.
- **Email**: Basic email format validation.
- **Phone Number**: U.S. phone format validation (e.g., 123-456-7890).
- **Password**: Requires at least 8 characters with at least one uppercase letter, one lowercase letter, and one number.
- **Confirm Password**: Ensures that it matches the password entered.

## Problem-Solving Approach

1. **Layout Creation**:
   - Divided the page into two main sections: the left side for static branding elements and the right side for the form.
   - Each section was enclosed in separate div containers to make styling and layout adjustments easier.

2. **Styling with CSS**:
   - Used CSS to style each component, focusing on background images, font styles, and responsive layouts.
   - Adjusted colors, button styles, and input fields to provide visual feedback for users, such as input validation highlighting.

3. **Form Design and Validation**:
   - Added input fields with appropriate types (`text`, `email`, `tel`, `password`), placeholders, and labels.
   - Implemented HTML5 validation patterns for each field, linked with CSS styles to change the border color based on validation success (green) or failure (red).

## Project Structure

```plaintext
sign-up-form-ToP/
├── index.html     # Main HTML file
├── style.css      # CSS file for styling
└── README.md      # This README file
```
### Technologies Used
- HTML5: Markup for structure and form elements.
- CSS3: Styles for layout, responsiveness, and validation feedback.

## Installation
To view this project locally:

1. Clone this repository
2. Open `index.html` in a web browser.
Project Outcome
The project reinforces knowledge of HTML and CSS, particularly focusing on form elements and input validation. By creating a structured layout and applying styles for visual feedback, this form provides an effective learning experience in front-end development and user interface design.

## Acknowledgements
This project is inspired by [The Odin Project](https://www.theodinproject.com/) curriculum.
## Author
Anthony Mendoza Reitor
---
© 2024 Anthony Mendoza Reitor
