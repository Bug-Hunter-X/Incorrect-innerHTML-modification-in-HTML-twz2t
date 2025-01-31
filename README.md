# Incorrect innerHTML Modification in HTML

This repository demonstrates a subtle and uncommon error in HTML related to modifying the innerHTML of an element.  The error lies in how the `getElementById` method is used to target the div and set its innerHTML.  The corrected version shows the proper usage.

## Bug

The `bug.html` file contains code that attempts to change the text content of a div element with the id "myDiv". However, it does so incorrectly resulting in a Javascript error.

## Solution

The `bugSolution.html` file shows the corrected implementation, properly selecting the element before modifying its innerHTML.