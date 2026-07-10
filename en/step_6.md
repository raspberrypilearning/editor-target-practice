## Add an arrow

The arrow will be drawn using a function.

## Step 1

Add a function to draw a sienna coloured circle at coordinates `200`, `200`.

```python line_numbers="true" line_number_start="9" line_highlights="10-14"
# The shoot_arrow function goes here
def shoot_arrow():
    arrow_x = 200
    arrow_y = 200
    fill('sienna')
    circle(arrow_x, arrow_y, 15)

```

## Step 2

Then call the function inside your `draw()` function.

```python line_numbers="true" line_number_start="35" line_highlights="37"
    fill('yellow')
    circle(200, 200, 30)
    shoot_arrow()

```

## Now run your code

![a brown arrow circle in the centre of the target](images/arrow-centre.png)

Click the **Run** button and check that the arrow appears in the centre of the target.
