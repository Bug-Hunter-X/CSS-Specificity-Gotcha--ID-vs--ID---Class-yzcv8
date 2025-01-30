# CSS Specificity Gotcha: ID vs. ID + Class

This repository demonstrates a subtle yet important issue related to CSS specificity.  The issue arises when an element has both an ID and a class, and there are conflicting styles applied through selectors targeting these attributes.

## The Problem
The `bug.css` file contains CSS rules where an element with both an ID and a class has conflicting styles defined. The expected behavior based on the combined selector might not align with the actual behavior due to how CSS specificity is calculated.

## The Solution
The `bugSolution.css` file presents a solution.  The approach addresses the specificity issue by providing guidance on how to write CSS rules to get the expected behavior.