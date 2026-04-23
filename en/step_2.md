<h2 class="c-project-heading--task">Draw the grass</h2>

➡️ Draw a green rectangle to represent the grass.

<h2 class="c-project-heading--explainer">Follow these instructions</h2>

Add a second light green rectangle (`rect`) at the bottom of the background.

<div class="c-project-code">
--- code ---
---
language: python
line_numbers: true
line_number_start: 19
line_highlights: 23-24
---
def draw():
# Things to do in every frame
    fill('cyan')
    rect(0, 0, 400, 250)
    fill('lightgreen')
    rect(0, 250, 400, 150)
--- /code ---
</div>

## Now run your code

Click the **Run** button. You should see the full background.

<div class="c-project-output">
![a blue rectangle over a green rectangle representing sky and grass](images/sky-grass.png)
</div>
### Debugging

<div class="c-project-callout c-project-callout--debug">

Make sure your code matches exactly and you have indented the code inside the function correctly. 

</div>

Confirm the observable result.
