# Tailwind CSS Hover Classes Not Working

This repository demonstrates a bug where Tailwind CSS hover classes are not applying correctly.  The expected behavior is that the div element should change color on hover, but this is not happening.

## Bug Description:
The hover effect on Tailwind CSS classes is not working as expected. The `hover:bg-blue-700` class is not changing the background color when hovering over the element.

## Solution:
The issue was resolved by ensuring that the correct Tailwind directives were added to the postcss.config.js and the purge option was set up properly.  Additionally, the correct build process was ensured to compile the tailwind directives properly.
