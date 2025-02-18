# JavaScript Null Check Bug

This repository demonstrates a common JavaScript bug related to handling null and undefined values in function parameters.  The `bug.js` file contains the erroneous code, while `bugSolution.js` provides a corrected version.

The bug arises from the function's incomplete null check.  While it explicitly checks for null values, it omits undefined values, leading to potential runtime errors or unexpected outputs. The solution enhances this check for a more reliable outcome.