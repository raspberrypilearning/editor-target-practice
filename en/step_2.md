## Draw the grass

➡️ Draw a green rectangle to represent the grass.

Add a second light green rectangle (`rect`) at the bottom of the background.

```python line_numbers="true" line_number_start="19" line_highlights="23-24"
def draw():
# Things to do in every frame
    fill('cyan')
    rect(0, 0, 400, 250)
    fill('lightgreen')
    rect(0, 250, 400, 150)
```

## Now run your code

![a blue rectangle over a green rectangle representing sky and grass](images/sky-grass.png)

> [!DEBUG]
> Make sure your code matches exactly and you have indented the code inside the function correctly.

Click the **Run** button and check that you see blue sky above green grass.
