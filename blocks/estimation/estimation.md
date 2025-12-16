# estimation.md

Purpouse of this block is to allow the user to select predefined Commerce features and estimations from the dropdown and create the complete estimation list with effort.

## Authering experince

 Author should be able to add block estimation to the page, 

## Block initial state

 Block should have dropdown with commerce feature and dropdown with Complexity and a plus button in the same row.  Second row should have a button to add new item just below the dropdown, Items of the dropdown is populated from the content/commerce-edge-calculator/en/data/commerce-features.json file. Data for the complexity can be hard code, simple, medium, large and complex. All the file name and styling should follow the default standard.

## Block user interaction 
- When user select an item from the commerce feature and click on the plus button, selected item should be added to the table and should displayed below dropdown. 
- When user click on the add new item button, a text filed and add button should be displayed as a second row. 
- When user click on the add new item item should be added to the table 

## Code Style Guidelines

### JavaScript
- Use ES6+ features (arrow functions, destructuring, etc.)
- Follow Airbnb ESLint rules (already configured)
- Always include `.js` file extensions in imports
- Use Unix line endings (LF)

**For detailed JavaScript guidelines:** Use the **building-blocks** skill which includes comprehensive decoration patterns and best practices.

### CSS
- Mobile-first responsive design (breakpoints: 600px/900px/1200px)
- All selectors scoped to blocks: `.{blockName} .selector`
- Follow Stylelint standard configuration

**For detailed CSS guidelines:** Use the **building-blocks** skill which includes comprehensive styling patterns and best practices.

### HTML
- Use semantic HTML5 elements
- Ensure accessibility standards (ARIA labels, proper heading hierarchy)
- Follow AEM markup conventions for blocks and sections
