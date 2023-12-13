# CSS Positioning Guide

This repository provides a comprehensive guide to CSS positioning, exploring the various position properties in CSS and their practical applications in web design.

## Introduction

Positioning in CSS is a fundamental concept that allows developers to control the layout of elements on a webpage. Understanding how to use position properties effectively is crucial for creating responsive and well-structured web designs.

## Position Properties

CSS offers several methods for positioning elements:

- **Static**: The default position of elements.
- **Relative**: Positions the element relative to its normal position.
- **Absolute**: Positions the element absolutely to its first positioned ancestor.
- **Fixed**: Positions the element relative to the browser window.
- **Sticky**: Positions the element based on the user's scroll position.

## Usage and Examples

### Static Positioning

By default, elements are positioned statically. Static positioned elements are not affected by the `top`, `bottom`, `left`, and `right` properties.

### Relative Positioning

`position: relative;` moves an element relative to its normal position.

Example:
```css
.box {
    position: relative;
    top: 10px;
    left: 20px;
}

# Absolute Positioning

position: absolute; positions an element relative to its nearest positioned ancestor.
Example:
css
Copy code
.container {
    position: relative;
}
.box {
    position: absolute;
    top: 0;
    right: 0;
}
# Fixed Positioning
position: fixed; positions an element relative to the viewport.
Example:
css
Copy code
.navbar {
    position: fixed;
    top: 0;
    width: 100%;
}
# Sticky Positioning
position: sticky; is a hybrid of relative and fixed positioning.
Example:
css
Copy code
.header {
    position: sticky;
    top: 0;
}