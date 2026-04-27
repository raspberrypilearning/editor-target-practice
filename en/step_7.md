<h2 class="c-project-heading--task">Make the arrow move</h2>

➡️ Make the arrow appear at random positions on the screen.

<h2 class="c-project-heading--explainer">Follow these instructions</h2>

Change the `arrow_x` and `arrow_y` variables so that each position is chosen by random numbers.

<div class="c-project-code">
--- code ---
---
language: python
line_numbers: true
line_number_start: 9
line_highlights: 11-12
---
# The shoot_arrow function goes here
def shoot_arrow():
    arrow_x = randint(100, 300)
    arrow_y = randint(100, 300)
    fill('sienna')
    circle(arrow_x, arrow_y, 15)

--- /code ---
</div>

## Now run your code

<div class="c-project-output">
![brown circle moving randomly around the target](images/random_arrow.gif)
</div>

Click the **Run** button and check that the arrow jumps around the target.
