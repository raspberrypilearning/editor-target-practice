<h2 class="c-project-heading--task">Detect mouse clicks</h2>

--- task ---

Comment out the line that prints the colour.

Define your `mouse_pressed()`{:.language-python} function under the comment `# The mouse_pressed function goes here`{:.language-python}. 

Add code to print the target emoji 🎯 when the mouse is clicked.

--- /task ---

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

<div class="c-project-code">
--- code ---
---
language: python
line_numbers: true
line_number_start: 5
line_highlights: 6,7
---

# The mouse_pressed function goes here    
def mouse_pressed():    
    print('🎯')

--- /code ---
</div>



**Test:** Click the **Run** button. You should see the 🎯 character printed when you click the mouse.

![target emoji printed when mouse clicked](images/target_printed.gif)