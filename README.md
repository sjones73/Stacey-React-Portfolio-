# React Portfolio

### Description
This project involves creating a personal portfolio using React, showcasing work samples, and deploying the application to Netlify. The goal is to create a modern, single-page application (SPA) that highlights your skills and projects in web development.

### User Story
As an employer looking for candidates with experience building single-page applications,
I want to view a potential employee's deployed React portfolio of work samples
So that I can assess whether they're a good candidate for an open position.

### Acceptance Criteria
Portfolio Structure:

Includes a header, a main content section, and a footer.
Header:

Displays the developer's name.
Contains navigation links with the following titles:
# About Me
# Portfolio
# Contact
# Resume
Highlights the title corresponding to the current section.
# Navigation:

Allows seamless navigation between sections without page reloading.
Defaults to the "About Me" section upon the first load.
# About Me Section:

Displays a recent photo or avatar of the developer.
Includes a short bio.
# Portfolio Section:

Displays titled images of six applications.
Each image includes links to:
The deployed application.
The corresponding GitHub repository.
Contact Section:

Includes a contact form with fields for:
Name
Email Address
Message
Validates required fields and displays notifications if:
A field is left empty.
An invalid email address is entered.
Resume Section:

Provides a downloadable link to the developer’s resume.
Lists the developer’s proficiencies.
Footer:

Displays text or icon links to:
The developer’s GitHub.
The developer’s LinkedIn profile.

### Technologies Used
React
CSS/SCSS for styling
Netlify for deployment

### Features Overview

# Navigation
Highlighted sections.
Smooth scrolling to respective sections.

# Portfolio Section
Includes six featured projects.
Links to both deployed applications and GitHub repositories.

# Contact Form
Validates user input for required fields and proper email format.
Notifies users of errors.

# Resume
Downloadable resume.
List of proficiencies displayed clearly.

# Footer
Links to professional profiles on GitHub and LinkedIn.

# Author
For inquiries or collaboration, contact me via LinkedIn or GitHub.

# Credit
My tutor Joem Casusi helped me with completing this assignment. 

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
