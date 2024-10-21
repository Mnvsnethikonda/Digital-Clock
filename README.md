# Digital-Clock

This HTML code creates a digital clock that displays the current time in hours, minutes, seconds, and AM/PM format, using an animated circular design.

### Key Features:

1. **HTML Structure**:
   - The clock is built using div elements to represent different time components: hours, minutes, seconds, and AM/PM.
   - Each time unit is enclosed in a circular design represented by SVG circles.

2. **CSS Styling**:
   - Uses the Google Font "Orbitron" for a digital clock effect.
   - The body is styled to center the clock on the page with a dark background.
   - Each time component is styled to show a rotating circular animation using `@keyframes`.
   - The circles rotate and change colors smoothly over time, creating a dynamic visual effect.

3. **JavaScript Functionality**:
   - The script updates the clock every second using `setInterval()`.
   - It retrieves the current time, formats it to a 12-hour clock, and updates the displayed values for hours, minutes, seconds, and AM/PM.
   - JavaScript ensures that single-digit numbers have a leading zero for consistency.

### Improvements or Corrections Needed:

1. **JavaScript Bug Fix**:
   - There is an issue in the script where it tries to update the stroke dash offset using `h.style.strokeDashoffset`, but `h`, `m`, and `s` are numbers, not elements. This needs to be corrected.

2. **Accessibility**:
   - Adding `aria-label` attributes to enhance screen reader compatibility would be a good improvement.

3. **Responsive Design Enhancements**:
   - Making the clock responsive for different screen sizes could improve usability across devices.

The current code provides a good starting point for a visually appealing digital clock with animation effects.
