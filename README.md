# Unexpected Cropping with `background-size: cover;`

This repository demonstrates a common issue encountered when using the `background-size: cover;` property in CSS. When applied to an element with a relatively small content area, the background image might be cropped or distorted unexpectedly. This is because `cover` attempts to scale the image to completely fill the element, maintaining aspect ratio, potentially resulting in parts of the image being cut off.

The `bug.css` file shows the problematic implementation, while `solution.css` offers a solution to mitigate this behavior.