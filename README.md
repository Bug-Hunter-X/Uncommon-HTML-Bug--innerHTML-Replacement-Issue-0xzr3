# Uncommon HTML Bug: innerHTML Replacement Issue

This repository demonstrates an uncommon bug related to using `innerHTML` in HTML to replace the content of a div.  The issue arises when attempting to append multiple paragraphs using string concatenation within `innerHTML`. The second paragraph does not render correctly.

## Bug Description

The bug involves using `innerHTML` to replace the content of a div with multiple paragraphs.  While the first paragraph appears correctly, the second paragraph gets swallowed up.

## Solution

The solution involves using DOM manipulation methods instead of directly manipulating innerHTML with string concatenation.  This allows for better control and avoids the unforeseen issues.
