# Tailwind CSS @apply Directive Bug with Complex Selectors

This repository demonstrates a bug encountered when using Tailwind CSS's `@apply` directive with complex class selectors that include pseudo-classes like `:hover`.

## Bug Description
The `@apply` directive, while convenient, can produce unexpected results when applied to selectors containing pseudo-classes or other complex situations. This often leads to styles not applying as expected.

## Reproduction
The `bug.html` file contains a button demonstrating the issue.  The hover effect's border change doesn't apply correctly. 

## Solution
The solution involves restructuring the CSS or avoiding the `@apply` directive in such complex cases, as shown in `bugSolution.html`.  Directly applying the styles tends to resolve the issue.