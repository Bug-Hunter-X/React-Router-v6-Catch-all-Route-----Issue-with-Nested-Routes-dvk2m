# React Router v6 Catch-all Route (*) Issue

This repository demonstrates a common issue encountered when using catch-all routes ("*") in React Router v6, specifically when those catch-all routes are nested within other routes.  The catch-all route might not correctly catch unmatched paths. 

## Problem

The provided `bug.js` demonstrates a scenario where the catch-all route is seemingly ignored, even when navigating to a path not explicitly defined.  This is often unexpected behavior leading to broken navigation.

## Solution

The `bugSolution.js` provides a solution that correctly implements the catch-all route.  The key fix involves placing the catch-all route at the top level of the route structure.