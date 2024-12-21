# Improperly Nested Paragraph Tags in HTML

This repository demonstrates an uncommon HTML error involving improperly nested paragraph tags (<p>).  Some browsers may handle this differently, leading to unexpected visual results or validation errors.

The `bug.html` file contains the problematic code.  The `bugSolution.html` file provides a corrected version.

**Bug:**  The inner `<p>` tag is nested within another `<p>` tag, which is not valid HTML.

**Solution:** The inner `<p>` tag should be removed or replaced with a different element (like a <span> or a div) to properly structure the content.