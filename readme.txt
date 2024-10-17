Overview
This project is a two-page website built using CSS Grid, Flexbox, and various SASS/SCSS features. It demonstrates modern CSS techniques for layout and styling while leveraging SASS for better organization and maintainability.

 Pages
1. index.html: The homepage introducing different trekking categories.
2. details.html: A detailed page with information on preparatio for trek.

 CSS Layouts

1. Trek Categories Section: Implemented using CSS Grid to organize the categories of treks in a responsive grid structure on the homepage. This layout allows the categories to adapt to different screen sizes, ensuring a user-friendly experience across devices.

2. Season Categories Section: Another CSS Grid layout is utilized on the details page to present the season categories. This grid ensures that information is displayed clearly and adjusts seamlessly for various screen widths, enhancing user engagement.

 Flexbox Layouts

1. Footer Section: The footer employs Flexbox to align and center its content, ensuring a clean and organized appearance across both pages. This layout style allows for easy adjustment of content alignment and spacing, resulting in a visually appealing footer.

2. Buttons Section: Flexbox is used to arrange buttons vertically on the homepage, centering them for improved usability. This approach enhances the button section’s accessibility and visual hierarchy, guiding users to important actions.

 SASS/SCSS Features

1. Variables: SASS variables for colors, fonts, and spacing are defined in a separate file. These variables are consistently used throughout the project, enabling quick adjustments to the design by changing values in one place.

2. Custom Properties: SASS variables are converted into CSS custom properties, allowing for dynamic styling across various components. This feature makes it easier to update styles globally without extensive changes to the CSS.

3. Nesting: SASS nesting is utilized extensively to structure styles hierarchically, improving code readability. This organization makes it simpler to manage styles related to specific components and maintain a clear relationship between parent and child elements.

4. Interpolation: Interpolation is used in several places to dynamically include variables in CSS properties. This flexibility allows for more complex styles to be defined without cluttering the code.

5. Mixins: Reusable mixins are created for common styles such as button styling and flex alignment. These mixins are included in various components to promote consistency and adhere to the DRY (Don't Repeat Yourself) principle.

6. Functions: A custom function is implemented to dynamically adjust color brightness for hover effects. This function ensures that the website maintains a consistent look and feel during user interactions, enhancing the overall user experience.

 File Structure
The SASS files are organized based on UI components and layout:

- SASS/: Contains all SASS files.
  - style.scss: Main SASS file.
  - _variables.scss: Contains defined variables for colors, fonts, and spacing.
  - _mixins.scss: Holds mixins for reusable styles throughout the project.
  - _layout.scss: Manages grid and flexbox layout styles for different sections.
  - _buttons.scss: Specific styles related to button components.
  - _footer.scss: Contains styles specifically for the footer section.

