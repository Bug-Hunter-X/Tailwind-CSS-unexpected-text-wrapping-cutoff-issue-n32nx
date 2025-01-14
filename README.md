# Tailwind CSS Unexpected Text Wrapping/Cutoff Bug

This repository demonstrates a bug encountered while using Tailwind CSS where text within a div element does not wrap correctly, resulting in unexpected text cutoff.  The issue seems to stem from an interaction between specific Tailwind CSS classes.  The `solution.html` file provides a corrected version with an explanation of the fix.

## Bug Description:

The paragraph text within the `div` in `bug.html` does not wrap properly, leading to truncation.  This may be due to an interaction between `p`, `text-xl`, `font-bold`, `mb-2`, `bg-gray-100`, `p-4`, `rounded-lg`, and `shadow-md` classes.

## Solution:

The `solution.html` file provides a fix.  The issue often arises from missing or improper use of  `break-words` utility class to enable text wrapping.

## How to Reproduce:

1.  Clone this repository.
2.  Open `bug.html` in a web browser.
3.  Observe the unexpected text truncation.
4.  Open `solution.html` to see the corrected behavior.