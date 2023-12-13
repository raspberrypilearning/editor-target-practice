<h2 class="c-project-heading--task">Finish the target</h2>

The archery target needs some more circles.

--- task ---

Add a smaller red and even smaller yellow triangle

<div class="c-project-code">
--- code ---
---
language: python
line_numbers: true
line_number_start: 22
line_highlights: 24,25,26,27
---
    fill('blue')  # Set the circle fill colour to blue
    circle(200, 200, 170)  # Draw the outer circle
    fill('red')  # Set the colour for the circle fill to red
    circle(200, 200, 110)  # Draw the inner circle using x, y, width
    fill('yellow')  # Set the colour for the circle fill to yellow      
    circle(200, 200, 30)  # Draw the middle circle using x, y, width

--- /code ---
</div>

**Run** your code again to see the full target

<div class="c-project-callout c-project-callout--tip">

### Tip
You can find a list of all of the available colour names on [W3Schools](https://www.w3schools.com/colors/colors_names.asp){:target="blank"}. 

</div>