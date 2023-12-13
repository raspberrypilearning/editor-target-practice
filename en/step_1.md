<h2 class="c-project-heading--task">Create a background</h2>

The [starter project](https://editor.raspberrypi.org/en/projects/target-practice-starter) has some code already written for you.


--- task ---

Click the run button, and you should see a blue rectangle.

--- /task ---

--- task ---

The sky has been drawn with a black border (stroke). 

Turn the stroke off for all shapes. Add `no_stroke()`{:.language-python} to the `setup`{:.language-python} function:

<div class="c-project-code">
--- code ---
---
language: python
line_numbers: true
line_number_start: 9
line_highlights: 12
---
def setup():
# Set up your game here
    size(400, 400)  # width and height of screen
    no_stroke()

--- /code ---
</div>

**Run** your code again. Did you notice that the border (stroke) has now disappeared?

<div class="c-project-callout c-project-callout--tip">

### Tip

Coordinates start from (x=0, y=0) in the top left-hand corner. This might be different to other coordinate systems you have used.

</div>

