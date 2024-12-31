# Unexpected Styling Due to Selector Specificity

This repository demonstrates a common yet often overlooked issue in CSS: problems arising from incorrect selector specificity.

The `bug.css` file contains CSS code that exhibits the issue of unexpected styling due to using selectors that are either too specific or not specific enough.

The `bugSolution.css` file provides a corrected version of the CSS, demonstrating how to use the appropriate level of specificity to achieve the desired styling.

## How to Reproduce
1. Clone this repository.
2. Open `bug.html` in a web browser.
3. Observe the unexpected styling.
4. Replace `bug.css` with `bugSolution.css`.
5. Observe the corrected styling.

## Key Learning
Understanding CSS selector specificity is crucial for writing efficient and predictable stylesheets.  Using the appropriate level of specificity avoids conflicts and ensures that styles are applied as intended.