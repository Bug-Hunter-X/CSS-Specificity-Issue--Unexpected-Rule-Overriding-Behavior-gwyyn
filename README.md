# CSS Specificity Issue: Unexpected Rule Overriding

This repository demonstrates a subtle issue related to CSS specificity.  The problem arises when combining ID and class selectors in ways that don't necessarily follow the expected specificity hierarchy.  The highest specificity selector is not always applied as the browser will follow its own precedence rules.

## Problem Description

The `bug.css` file contains CSS rules that illustrate this issue. You might expect the most specific selector to always win, but that's not always the case. The browser's handling of specificity can lead to unexpected results.  The specificity calculation of CSS is not straightforward and can be counterintuitive for developers.

## Solution

The `bugSolution.css` file shows a possible solution using different ways to solve the problem.