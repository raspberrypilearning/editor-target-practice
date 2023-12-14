<h2 class="c-project-heading--task">Add an arrow</h2>

--- task ---
The archery target needs some more circles.

Add an even small circle to represent an arrow.

<div class="c-project-code">
--- code ---
---
language: python
line_numbers: true
line_number_start: 22
line_highlights: 24,25,26,27
---
# The shoot_arrow function goes here
def shoot_arrow():
    arrow_x = 200
    arrow_y = 200
    fill('sienna')
    circle(arrow_x, arrow_y, 15)

--- /code ---
</div>

Call your function inside your `draw()`{:.language-python} function.

<div class="c-project-code">
--- code ---
---
language: python
line_numbers: true
line_number_start: 33
line_highlights: 35
---
    fill('yellow')
    circle(200, 200, 30)
    shoot_arrow()

--- /code ---
</div>

--- /task ---

**Run** your code again to see the arrow in the centre