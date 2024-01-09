<h2 class="c-project-heading--task">Get the colour</h2>

--- task ---

Add a **global variable** called `hit_colour`{:.language-python} that can be used throughout your code. Then `get()`{:.language-python} the colour at `arrow_x, arrow_y`{:.language-python} and `print()`{:.language-python} it out.

<div class="c-project-code">
--- code ---
---
language: python
line_numbers: true
line_number_start: 9
line_highlights: 11, 14, 15
---
# The shoot_arrow function goes here     
def shoot_arrow():
    global hit_colour  # Can be used in other functions  
    arrow_x = randint(100, 300)  
    arrow_y = randint(100, 300) 
    hit_colour = get(arrow_x, arrow_y).hex
    print(hit_colour)
    fill('sienna')
    circle(arrow_x, arrow_y, 15)

--- /code ---
</div>

--- /task ---

**Test:** Click the **Run** button. You should see the colours being printed in the **Text output**.

<div class="c-project-callout c-project-callout--tip">

### Tip
Make sure you are in **Split view** so that you can see the **Text output** and the **Visual output**.

The codes you see printed are the hexidecimal representations of the colours.

</div>


