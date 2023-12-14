<h2 class="c-project-heading--task">Make the arrow move</h2>

--- task ---
The arrow needs to move randomly

change the `arrow_x`{:.language-python} and `arrow_y`{:.language-python} variables so that are chosen each frame by random numbers.

<div class="c-project-code">
--- code ---
---
language: python
line_numbers: true
line_number_start: 8
line_highlights: 9, 10
---
# The shoot_arrow function goes here
def shoot_arrow():
    arrow_x = randint(100, 300)
    arrow_y = randint(100, 300)
    fill('sienna')
    circle(arrow_x, arrow_y, 15)

--- /code ---
</div>

--- /task ---

**Run** your code again to see the arrow jump around the target.