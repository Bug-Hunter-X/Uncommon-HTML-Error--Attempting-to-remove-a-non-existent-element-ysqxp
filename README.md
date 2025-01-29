# Uncommon HTML Bug: Removing a Non-Existent Element

This repository demonstrates a common yet easily overlooked error in JavaScript when interacting with the DOM: attempting to remove an element that doesn't exist.  The provided code attempts to remove a div element but fails if that element is not found within the DOM. The solution shows how to properly handle this scenario to prevent errors.

## Bug
The `bug.html` file contains the problematic code. The `myFunction` attempts to remove an element using `remove()` without checking if the element actually exists.