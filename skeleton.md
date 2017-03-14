What happens to the layout when you resize the screen to less than 550 px?
How do you think it works?

The layout changed from being multiple columns sharing a row to a single column per row being next to one another. It works by having a default state mobile-first. It looks different on a larger a screen because skeleton uses @media queries for scaling across devices.
