# FormCraft — Professional Form Styling

**A modern, responsive appointment request form built with HTML5 and CSS3.**

FormCraft is a front-end development project focused on creating clean, accessible, and responsive web forms using semantic HTML and modern CSS techniques. It features carefully styled input fields, custom radio buttons and checkboxes, visual validation states, and responsive layouts designed to provide a consistent user experience across desktop, tablet, and mobile devices.

The project demonstrates how thoughtful interface design and well-structured code can transform a standard HTML form into a polished web experience—all without requiring JavaScript.

---

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technologies](#technologies)
- [Project Preview](#project-preview)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Accessibility](#accessibility)
- [Responsive Design](#responsive-design)
- [Learning Objectives](#learning-objectives)
- [Future Improvements](#future-improvements)
- [Limitations](#limitations)
- [Author](#author)
- [License](#license)

---

## Overview

FormCraft provides a professional appointment request interface where users can enter their contact information, select an appointment type, choose a preferred date and time, specify a meeting method, and provide additional details.

The design emphasizes usability, visual consistency, accessibility-conscious styling, and responsive behavior.

### Project Details

| Attribute | Description |
|---|---|
| Project Name | FormCraft |
| Project Type | Front-End Web Development |
| Primary Technologies | HTML5 and CSS3 |
| Layout | CSS Grid and Flexbox |
| Responsive Design | Desktop, tablet, and mobile |
| JavaScript | Not required for the current implementation |
| Form Processing | Front-end demonstration only |
| Repository | [FormCraft on GitHub](https://github.com/Regalson001/FormCraft) |
| Author | Stephen Oyugi |

---

## Features

### Professional Interface
- Clean, modern, and minimal design.
- Consistent typography, spacing, and color palette.
- Card-based form layout with subtle shadows.
- Rounded input fields and carefully styled components.
- Clear visual hierarchy and intuitive form sections.

### Comprehensive Form Fields
- First and last name inputs.
- Email address and telephone number fields.
- Appointment type selection.
- Preferred appointment date.
- Date-and-time selection using `datetime-local`.
- Radio buttons for meeting preferences.
- Textarea for additional information.
- Required consent checkbox.
- Styled submission button.

### Interactive Styling
- Input hover and focus states.
- Custom checkbox and radio button appearances.
- Distinct invalid-input styling.
- Animated checkmarks and selection indicators.
- Button hover and active effects.
- Consistent transitions across interactive components.

### Responsive Layout
- Two-column form layout on wider screens.
- Single-column layout on smaller screens.
- Flexible component sizing.
- Responsive typography and spacing.
- Mobile-friendly buttons and controls.

### Native HTML Validation
- Required-field validation.
- Email format validation.
- Appropriate input types for dates and contact information.
- Character limits for additional messages.

### Accessibility-Conscious Design
- Semantic HTML5 structure.
- Explicit labels for form controls.
- Grouped controls using `fieldset` and `legend`.
- Visible keyboard focus indicators.
- Reduced-motion support.
- Accessible native input elements behind custom styling.

---

## Technologies

| Technology | Purpose |
|---|---|
| HTML5 | Semantic structure and form elements |
| CSS3 | Styling, layout, and interactive states |
| CSS Grid | Responsive form-field arrangement |
| Flexbox | Component alignment and flexible layouts |
| CSS Custom Properties | Reusable design tokens |
| CSS Pseudo-classes | Focus, hover, checked, and validation states |
| CSS Pseudo-elements | Custom control indicators |
| CSS Media Queries | Responsive behavior |
| Google Fonts | DM Sans and Manrope typography |
| Git | Version control |
| GitHub | Source code hosting |

---

## Project Preview

The interface features a clean visual identity with a purple accent color, a light background, structured form sections, and responsive input layouts.

**Design highlights:**
- Primary color: `#635bff`
- Background color: `#f5f7fc`
- Surface color: `#ffffff`
- Primary text: `#182230`
- Secondary text: `#667085`
- Error color: `#c62828`

These colors are managed through CSS custom properties, making the design easy to maintain and customize.

> **Preview images:** Screenshots can be added to this section once captured from the completed project.

For example, save a screenshot as `screenshots/formcraft-preview.png` and add:

```markdown
![FormCraft appointment form preview](screenshots/formcraft-preview.png)
```

---

## Project Structure

```text
FormCraft/
├── index.html
├── styles.css
├── README.md
└── LICENSE
```

| File | Description |
|---|---|
| `index.html` | Defines the appointment form structure and content |
| `styles.css` | Contains styling, responsive layouts, and interactive states |
| `README.md` | Provides project documentation |
| `LICENSE` | Contains the MIT License terms |

---

## Getting Started

### Prerequisites

To run this project locally, you need:

- A modern web browser.
- [Visual Studio Code](https://code.visualstudio.com/).
- [Git](https://git-scm.com/) for cloning the repository.
- An internet connection to load Google Fonts.

### 1. Clone the Repository

Open your terminal and run:

```bash
git clone https://github.com/Regalson001/FormCraft.git
```

### 2. Navigate to the Project Folder

```bash
cd FormCraft
```

### 3. Open the Project in VS Code

```bash
code .
```

Alternatively, open the folder manually using **File → Open Folder** in Visual Studio Code.

### 4. Launch the Project

Open `index.html` directly in your browser.

For a convenient development workflow, you can install the Live Server extension in VS Code, right-click `index.html`, and select **Open with Live Server**.

The form will open in your default browser.

---

## Accessibility

FormCraft incorporates accessibility-conscious practices intended to improve usability for different users and input methods.

### Semantic Structure
HTML elements such as `<header>`, `<main>`, `<section>`, `<form>`, `<fieldset>`, `<legend>`, and `<footer>` communicate the page structure.

### Associated Labels
Form controls use descriptive labels connected through matching `for` and `id` attributes.

### Keyboard Navigation
Visible focus indicators help keyboard users identify the currently focused interactive element.

### Validation Feedback
CSS demonstrates invalid-input styling, while native HTML attributes provide basic browser validation.

A production implementation should also provide clear error messages associated with the relevant controls.

### Reduced Motion
The `prefers-reduced-motion` media query reduces transitions and animations for users who prefer reduced motion.

**Accessibility note:** These features support accessible design, but the project has not been independently audited for full WCAG conformance.

---

## Responsive Design

FormCraft uses CSS Grid, Flexbox, flexible dimensions, and media queries to adapt to different screen sizes.

| Screen Size | Layout |
|---|---|
| Desktop | Two-column form fields and spacious content |
| Tablet | Flexible content width and adjusted spacing |
| Mobile | Single-column fields and stacked meeting options |

The design aims to maintain readability, consistent spacing, and comfortable interaction across devices.

---

## Learning Objectives

This project provides practical experience with:

- Structuring forms using semantic HTML5.
- Selecting appropriate input types.
- Associating labels with form controls.
- Grouping related fields with `fieldset` and `legend`.
- Applying native HTML validation attributes.
- Styling interactive states using CSS pseudo-classes.
- Creating custom checkbox and radio button appearances.
- Building layouts with CSS Grid and Flexbox.
- Using CSS custom properties for maintainable styling.
- Applying media queries for responsive design.
- Improving keyboard navigation and form usability.
- Organizing a project for GitHub.

---

## Future Improvements

Potential enhancements include:

- [ ] Add JavaScript-powered validation messages.
- [ ] Provide accessible, field-specific error messages.
- [ ] Prevent selection of past appointment dates.
- [ ] Add a success message after submission.
- [ ] Connect the form to a backend API.
- [ ] Store appointment requests in a database.
- [ ] Implement email confirmations.
- [ ] Add loading and submission states.
- [ ] Test accessibility with automated tools and assistive technologies.
- [ ] Conduct cross-browser and responsive-design testing.

---

## Limitations

FormCraft is currently a front-end demonstration.

- Form submissions are not saved to a database.
- No backend service processes appointment requests.
- No confirmation emails are sent.
- Appointment availability is not checked.
- HTML validation does not replace server-side validation.
- The displayed privacy message does not implement a complete data-protection system.

A production implementation would require a backend, server-side validation, secure data handling, and appointment-management functionality.

---

## Author

**Stephen Oyugi**  
*Front-End Developer in Training | HTML5 & CSS3*

I am a front-end development learner focused on building clean, responsive, and accessible web interfaces. My current interests include semantic HTML, modern CSS techniques, responsive layouts, and practical projects that strengthen my understanding of web development.

My goal is to build better web experiences, one project at a time.

**GitHub:** [@Regalson001](https://github.com/Regalson001)

**Project Repository:** [FormCraft](https://github.com/Regalson001/FormCraft)

---

## License

FormCraft is licensed under the **MIT License**.

You are permitted to use, copy, modify, merge, publish, distribute, sublicense, and sell copies of the software, subject to the conditions of the license.

The MIT License requires the original copyright notice and permission notice to be included in copies or substantial portions of the software.

See the [`LICENSE`](LICENSE) file for the complete terms.

---

<p align="center">
  <strong>FormCraft</strong><br>
  Thoughtful design. Responsive layouts. Better web experiences.
</p>
