# timetable-2024-25
# Master Timetable 2024/2025 Academic Year

## Project Description

This project recreates the school's master timetable for the 2024/2025 academic year using semantic HTML and CSS. The timetable displays the weekly schedule for years 7-11 across five days (Monday-Friday) with 13 time periods, including breaks, lunch, and end-of-day activities.

## Implementation Details

### HTML Structure
- Uses semantic HTML with proper `<table>`, `<thead>`, and `<tbody>` elements
- Implements `<th>` tags with appropriate `scope` attributes for accessibility
- Utilizes `rowspan` and `colspan` attributes to merge cells for breaks, lunch periods, and activities
- Follows W3C HTML validation standards

### CSS Styling
- Consistent border styling throughout the table
- Sans-serif font family for readability
- Centered text alignment with appropriate padding
- Distinct background colors for different cell types:
  - Light gray for headers and year groups
  - Yellow for break periods
  - Green for lunch periods
  - Pink for end-of-day activities
  - White for subject cells
- Vertical text orientation for merged cells to save space

### Layout Features
- Fixed-width layout centered on the page
- Responsive font sizes for different screen contexts
- Print-friendly styles included

## Accessibility Considerations

1. **Semantic HTML**: Uses proper table structure with `<thead>` and `<tbody>` elements
2. **Table Headers**: All header cells use `<th>` with appropriate `scope="col"` or `scope="row"` attributes
3. **Screen Reader Compatibility**: Logical table structure ensures proper navigation for assistive technologies
4. **Color Contrast**: Sufficient contrast between text and background colors
5. **Alt Text**: The timetable preview image includes descriptive alt text: "Master timetable showing weekly schedule for years 7-11 with subject allocations, breaks, and activities"

## File Structure
- `index.html` - Main HTML file containing the timetable structure
- `style.css` - CSS stylesheet with all styling rules
- `README.md` - This documentation file
- `timetable_preview.png` - Screenshot of the completed timetable

## Browser Compatibility
The timetable has been designed to work across modern browsers including:
- Chromebrowsers
- Firefox
  

## Validation
Both HTML and CSS files have been structured to pass W3C validation:
- HTML validation: Uses semantic elements and proper nesting
- CSS validation: Uses standard CSS properties and values

## Notes
The timetable accurately reflects the master schedule provided, including:
- All subject codes and room numbers
- Proper time slot allocations
- Break and lunch period spans
- End-of-day activity periods
- Teacher reference numbers in the footer
