<h2 class="c-project-heading--task">Create a background</h2>

--- task ---
The starter project to the right has some code already written for you.

Click the run button, and you should see a blue rectangle.

The sky has been drawn with a black border (stroke). 

Turn the stroke off for all shapes. Add `no_stroke()`{:.language-python} to the `setup`{:.language-python} function.

 --- /task ---

<div class="c-project-code">
--- code ---
---
language: python
line_numbers: true
line_number_start: 13
line_highlights: 16
---
def setup():
# Set up your game here
    size(400, 400)  # width and height of screen
    no_stroke()

--- /code ---

</div>

**Test:** Click the **Run** button again. Did you notice that the border (stroke) has now disappeared?

![image of a blue rectangle](images/sky.png)

<div class="c-project-callout c-project-callout--tip">

### Tip

Coordinates start from (x=0, y=0) in the top left-hand corner. This might be different to other coordinate systems you have used.

If you see an alert "Execution interrupted" when you click stop on your program, don't be concerned. This just means the normal flow of the program was stopped.

</div>

