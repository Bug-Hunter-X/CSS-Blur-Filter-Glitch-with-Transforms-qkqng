# CSS Blur Filter Glitch with Transforms

This repository demonstrates a subtle bug related to the interaction between the CSS `filter: blur()` property and the `transform` property.  Specifically, applying a blur filter to an element that also has a transform applied can lead to unexpected visual artifacts or glitches in certain browsers. This is due to inconsistencies in how browsers handle the bounding box calculations for transformed elements when performing the blur operation.

The `bug.css` file shows the problematic code, while `bugSolution.css` offers potential workarounds.

**Problem:** The blur filter doesn't consistently interact with transformed elements, leading to visual distortion.

**Solution:**  Alternative techniques such as using a separate blurred element to achieve the desired effect are provided.