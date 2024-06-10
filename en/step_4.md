<h2 class="c-project-heading--task">Add a target circle</h2>

--- task ---

➡️ Draw a circle to represent a target.

--- /task ---

The archery target needs some circles attached to the stand.

The largest part of the target is a blue **circle**.

Draw a circle by providing x and y coordinates for its centre, and a width.

<div class="c-project-code">
--- code ---
---
language: python
line_numbers: true
line_number_start: 25
line_highlights: 27-28
---
    fill('sienna')
    triangle(150, 350, 200, 150, 250, 350)
    fill('blue')
    circle(200, 200, 170)

--- /code ---
</div>


**Test:** Click the **Run** button. You should see the target.

![a blue circle representing the target area](images/blue-circle.png)

