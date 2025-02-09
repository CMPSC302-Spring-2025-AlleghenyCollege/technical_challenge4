### Technical Challenge 4: CSS Layouts

## Deadline: February 14, 2025 by 10am

---

### Overview

In this challenge, you will:

  - Understand how CSS positioning, Flexbox, and Grid compare.
  - Practice building responsive web layouts.
  - Gain experience using media queries for different screen sizes.
  - Explore best practices for structuring and documenting CSS files.

## Resources
- [CSS Fundamentals](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/CSS_basics)
- [Flexbox Guide](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox)
- [Grid Guide](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Grids)

## Requirements

#### **Task 1: Build a Portfolio Layout with Grid**
1. Create a portfolio layout with at least three sections:
   - **Header**: A navigation bar with links.
   - **Main Content**: A two-column layout with an image on the left and text on the right.
   - **Footer**: A simple footer with some links or text.

2. Implement the layout using **CSS Grid**:
   - Define at least two rows and two columns in your grid.
   - Use `grid-template-columns` and `grid-template-rows` to organize the layout.
   - Ensure the layout is responsive: use media queries to adjust the layout for smaller screens (e.g., switch to a one-column layout when the screen width is below 600px).
   - Use `grid-template-columns` and `grid-template-rows` to arrange sections. Set media queries to switch to a single-column layout on smaller screens.
   - **How to get started with Grid**:
     - Link `grid.html` to your `grid.css` file.
     - Wrap your header, main content, and footer in a container with a class like `.grid-container`.
     - In your `grid.css`, set `display: grid` on `.grid-container`, then define columns and rows using `grid-template-columns` and `grid-template-rows`.
     - Use media queries to change `grid-template-columns` to a single column for smaller screens.

#### **Task 2: Build the Same Layout with Flexbox**
1. Create the same portfolio layout but using **CSS Flexbox**.
2. Use `flex-direction`, `justify-content`, and `align-items` to organize the sections.
3. Ensure the layout is responsive using media queries, similar to your grid layout.
   - Explanation: Use `flex-direction`, `justify-content`, and `align-items` to mirror the grid layout. Adapt it with media queries for responsiveness.
   - **How to get started with Flexbox**:
     - Link `flexbox.html` to your `flexbox.css`.
     - Wrap your header, main content, and footer in a container with a class like `.flex-container`.
     - In your `flexbox.css`, set `display: flex` on `.flex-container`, then control the layout with properties like `flex-direction`, `justify-content`, and `align-items`.
     - Use media queries to adjust the layout for smaller screens (e.g., switch from `row` to `column`).

#### **Task 3: Write a Report**
- In your report compare your Flexbox and Grid approaches.

#### **Submission Requirements:**
- Submit your code in the GitHub repository.
- Include images in `report.md` illustrating the layouts of locally rendered pages.
- Answer all prompts in the report.

---

**Evaluation Criteria:**
- [ ] Correct use of CSS Grid for Task 1
- [ ] Correct use of Flexbox for Task 2
- [ ] Responsive design with media queries
- [ ] Clear comparison in  `report.md`
- [ ] Images included in report.md
- [ ] Code is organized and clear
