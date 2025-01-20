# Tailwind CSS Flexbox Unexpected Vertical Stacking Bug

This repository demonstrates a common issue encountered when using Tailwind CSS's flexbox utilities.  The problem occurs when flex items unexpectedly stack vertically instead of horizontally, even when the `flex` class is applied. This typically happens when the parent container lacks sufficient horizontal space.

## Bug Description

The provided HTML uses Tailwind CSS to style two divs within a flex container.  Despite using the `flex` class, the divs stack vertically if the window width is too small.

## Solution

The solution involves ensuring that the parent container has enough horizontal space or using Tailwind's responsive modifiers to adjust layout based on screen size.