# Incorrect Element Selection in HTML
This repository demonstrates a common mistake when selecting elements within HTML using JavaScript.

The bug involves attempting to access an inner element using `getElementById` and then using `textContent` to retrieve its text.  This does not correctly select the inner element's text.  The solution shows the correct usage of `querySelector` for selecting inner elements. 

## Bug
The `bug.html` file shows how `getElementById` returns the outer element and thus textContent returns the combined text of all children.

## Solution
The `bugSolution.html` file provides a corrected version, utilizing `querySelector` to accurately select the inner paragraph and extract its content.
