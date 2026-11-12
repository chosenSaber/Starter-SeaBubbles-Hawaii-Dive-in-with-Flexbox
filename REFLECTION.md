# SeaBubbles Hawaii — Reflection

## CSS Property Experiments

**1. Gap Property**

I used the `gap` property in the course grid to control the spacing between the cards. Setting `gap: 20px` gives the cards consistent spacing without having to add margins to each one. Increasing the gap would spread the cards farther apart, while decreasing it would bring them closer together.

**2. Flex-Basis Property**

I used `flex-basis` to control how much space each course card takes up. Setting it to `100%` makes the cards stack vertically, while `40%` allows two cards per row and `20%` allows four. I also used `flex-grow: 1` so the cards could expand to fill the available space.

## Responsive Breakpoints

I used a mobile-first approach with two media queries. At widths below 768px, the cards display in one column. At 768px, they change to two columns, and at 992px, they change to four columns. These breakpoints make the website easier to navigate on phones, tablets, and desktops. I also used Flexbox wrapping to help the navigation and other content adjust to smaller screens.

## Bug Fix

One layout issue from the starter website was that the hero image was too large. This was addressed by adding `width: 100%` and `height: auto` to the `.hero img` CSS rule. This allows the image to fit the width of its container while keeping its original proportions instead of stretching or overflowing.

## What I Learned

This assignment helped me better understand how Flexbox and media queries work together to create responsive layouts. I learned how properties like `flex-basis`, `flex-grow`, `flex-wrap`, and `gap` affect the positioning and spacing of elements on different screen sizes.
