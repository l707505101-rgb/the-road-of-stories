MODULE 2 · LIVING AND SPENDING — FIXED NAVIGATION

Fixes:
- Module navigation now opens the selected block and performs one stable scroll.
- Removed smooth-scroll behavior that could chase a changing iframe layout.
- Removed ResizeObserver/window-resize feedback loops between child blocks and the parent.
- Block heights update only on load and when an accordion toggle changes the content.
- Existing block content and media are preserved.
