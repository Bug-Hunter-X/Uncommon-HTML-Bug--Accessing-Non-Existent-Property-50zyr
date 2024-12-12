# Uncommon HTML Bug: Accessing Non-Existent Property

This repository demonstrates a subtle bug in HTML that involves attempting to access a non-existent property of a DOM element. While seemingly simple, this type of error can be difficult to track down as it may not always result in a clear error message.

The bug is in `bug.html`.  The solution is provided in `solution.html`.

## Bug Description

The code attempts to access a property (`nonExistentProperty`) that doesn't exist on the `myDiv` element.  Different browsers might handle this differently, some might return `undefined`, others might throw an error, making debugging difficult.

## Solution

Always check if a property exists before accessing it to prevent this type of error.  The improved code in `solution.html` demonstrates this.