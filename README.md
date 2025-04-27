# How-Long-to-Earn-an-Amount-of-Money-Calculator-

This is a lightweight HTML, CSS, and JavaScript tool designed to calculate the time needed to accumulate specific monetary targets based on user-selected earnings and frequency.

Key technical elements:

Dynamic Form Handling:

Multiple <select> dropdowns allow users to pick two financial targets, their earnings per unit of time, and earning frequency (second, minute, hour, day, week).

An optional custom input field is revealed via JS if "Custom" is selected.

Calculation Logic:

Earnings are normalised to per-second rates, then total seconds required for each target are calculated.

Final dates are computed by adding the total seconds (converted to milliseconds) to the user-selected start date.

Time Formatting:
JavaScript formats results into approximate days, months, and years for easier understanding.

Animated Background:
CSS @keyframes create a slow-shifting animated gradient, giving the page a modern, visually pleasing look without affecting performance.

Validation:
The calculator includes basic input validation to prevent invalid or missing custom amounts.

Project is built with no external dependencies — only vanilla JavaScript and CSS animations.
