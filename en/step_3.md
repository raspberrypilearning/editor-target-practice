<h2 class="c-project-heading--task">Draw a stand</h2>

--- task ---

Your game needs a target to shoot arrows at.

Add a brown triangle to your foreground.

--- /task ---

<div class="c-project-code">
--- code ---
---
language: python
line_numbers: true
line_number_start: 23
line_highlights: 25-26
---
    fill('lightgreen')
    rect(0, 250, 400, 150)
    fill('sienna')
    triangle(150, 350, 200, 150, 250, 350)
--- /code ---
</div>


**Test:** Click the **Run** button. You should see the triangle.

<div class="c-project-callout c-project-callout--tip">

![A brown triangle on grass and against a sky.](images/target-stand.png){:width="400px"}

