---
title: "Date & Time Picker"
layout: "single"
description: "Allows the user to select a single date, a date range, or time."
components: true
componentsWeb: true
images:
  - "/img/components/headers/date-time-picker.png"
component: date-time-picker
keywords: menu
tags: [accessibility]
---

## Accessibility

- Make sure the user can interact with the Date & Time Picker using the keyboard. To give the input keyboard focus, use the `tab` key (or `shift` + `tab` when tabbing backwards)
- To activate the calendar popover, use the `enter`/`return` or `space` keys when the calendar icon is in focus.
- To activate the input, use the `enter`/`return` or `space` keys.
- Use a wrapping `<nav>` element to identify the calendar popover as a navigation section to screen readers and other assistive technologies. Provide a descriptive `aria-label` (for example, "Pick a date" or "Pick a date range") for the `<nav>` to reflect its purpose.
- Be sure to add `aria-label="Previous"` and ` aria-label="Next"` attributes to the previous/ next icons in the date picker.
- Provide clear and informative error messaging to help users understand what they needs to do to rectify the problem.
