<h2 class="c-project-heading--task">Detect mouse clicks</h2>

--- task ---

➡️ Print a target emoji 🎯 when the mouse button is pressed.

--- /task ---

Comment out the line that prints the colour.

<div class="c-project-code">
--- code ---
---
language: python
line_numbers: true
line_number_start: 14
line_highlights: 15
---
    hit_colour = get(arrow_x, arrow_y).hex
    # print(hit_colour)
    circle(arrow_x, arrow_y, 15)
--- /code ---
</div>


Add code to print the target emoji 🎯 when the mouse is clicked.

<div class="c-project-code">
--- code ---
---
language: python
line_numbers: true
line_number_start: 5
line_highlights: 6-7
---
# The mouse_pressed function goes here    
def mouse_pressed():    
    print('🎯')
--- /code ---
</div>



**Test:** Click the **Run** button. You should see the 🎯 character printed when you click the mouse.

![target emoji printed when mouse clicked](images/target_printed.gif)

<div class="c-project-callout c-project-callout--tip">

### Tip

The `mouse_pressed()`{:.language-python} function is automatically called by the `p5` library when the left mouse button is pressed.

</div>