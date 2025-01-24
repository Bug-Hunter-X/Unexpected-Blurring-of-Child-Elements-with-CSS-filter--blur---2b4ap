# CSS filter: blur() Bug

This repository demonstrates a common issue with the CSS `filter: blur()` property where applying it to a parent element unintentionally blurs its children.  The solution provided shows how to avoid this problem.

## Bug Report

When applying `filter: blur()` to a parent element, all child elements within that parent also become blurred. This can be undesirable when specific elements should remain crisp and clear.  See `blurBug.css` for an example.

## Solution

The solution utilizes the `filter` property on specific elements rather than applying it to the parent.  This allows for granular control over which elements are blurred. View `blurSolution.css` for the fix.