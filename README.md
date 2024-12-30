# CSS `calc()` Unexpected Behavior in Media Queries

This repository demonstrates a peculiar issue with the CSS `calc()` function when used with percentages within media queries.  The expected calculation doesn't always occur correctly.

## Problem

The `width: calc(100% - 20px);` rule, intended to set the width to 100% of the container minus 20px, does not consistently behave as expected within a media query.  The 20px subtraction might not be applied correctly, leading to inconsistent layout.

## Solution

The issue might stem from the order of operations or how the browser interprets the percentage calculation within the media query context.  The solution provided uses a different approach to achieve the desired layout, possibly using a combination of padding, margin, or absolute positioning.