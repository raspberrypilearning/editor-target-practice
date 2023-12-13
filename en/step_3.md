<h2 class="c-project-heading--task">Draw a stand</h2>

Your game needs a target to shoot arrows at.

--- task ---

The sky has been drawn with a black border (stroke). 

Turn the stroke off for all shapes. Add `no_stroke()` to the `setup` function:

<div class="c-project-code">
--- code ---
---
language: python
line_numbers: true
line_number_start: 18
line_highlights: 20-21
---
    fill('lightgreen')
    rect(0, 250, 400, 150)
    fill('sienna')
    triangle(150, 350, 200, 150, 250, 350)
--- /code ---
</div>

--- /task ---
In Python, `print()`{:.language-python} outputs text (words or numbers) to the screen.
Type the code to `print()`{:.language-python} Hello to the screen:

--- /task ---

**Run** your code again to see the triangle

<div class="c-project-callout c-project-callout--tip">

![A brown triangle on grass and against a sky.](images/target-stand.png){:width="400px"}

