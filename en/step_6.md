<h2 class="c-project-heading--task">Add an arrow</h2>

--- task ---

Add an even smaller circle to represent an arrow.

This circle will be drawn using a function.

Add a function to draw another circle at coordinates `200`, `200`.

Then call your function inside your `draw()`{:.language-python} function.

--- /task ---


<div class="c-project-code">
--- code ---
---
language: python
line_numbers: true
line_number_start: 9
line_highlights: 10-14
---
# The shoot_arrow function goes here
def shoot_arrow():
    arrow_x = 200
    arrow_y = 200
    fill('sienna')
    circle(arrow_x, arrow_y, 15)

--- /code ---
</div>

<div class="c-project-code">
--- code ---
---
language: python
line_numbers: true
line_number_start: 35
line_highlights: 37
---
    fill('yellow')
    circle(200, 200, 30)
    shoot_arrow()

--- /code ---
</div>


**Test:** Click the **Run** button. You should see the arrow in the centre.

![a brown arrow circle in the centre of the target](images/arrow-centre.png)