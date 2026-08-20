This repository has received an automated update that improves index.html for accessibility, validation, and rendering.

Changes included:
- Moved navigation into header and added semantic structure (header/main)
- Improved accessibility (aria-live, role=alert, aria-describedby)
- Added input validation (min/max/required) and contextual hints
- Debounced input handling and refactored JavaScript into small functions
- Scaled the canvas for devicePixelRatio for crisper drawing on HiDPI displays
- Show clearer warning when projection is invalid (peak flow ≤ rest flow)

See the branch: improve/index-html-accessibility
