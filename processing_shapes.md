---
layout: page
title: Shapes
within: programming
---

<details class="prereq" markdown="1"><summary>Assumed Knowledge</summary>

<!--  * <a href="./lists">Lists</a>
  * <a href="./loops">Loops</a>-->
</details>

<details class="outcomes" markdown="1"><summary>Learning Outcomes</summary>
  * Learning about the basic shapes in Processing.
</details>

## Author: Gaurav Gupta

## Shape 1 - point

Syntax:

```
point(x, y); //draws point at (x, y)
```

Example:

```
point(20, 80); //20 to the right and then 80 down
point (50, 40); //50 to the right and then 40 down
```

## Shape 2 - line

Syntax:

```
line(x1, y1, x2, y2); //draws line between (x1, y1) and (x2, y2)
```

Example:

```
line(20, 80, 50, 40); //line between (20, 80) and (50, 40)
line(10, 20, 80, 20); //line between (10, 20) and (80, 20)
```

<details>
<summary>
What can you tell about lines where y1 is the same as y2? For example, `line(10, 20, 80, 20)`. What about the lines where x1 is the same as x2? For example, `line(30, 10, 30, 90)`.
</summary>
<solution>
When y1 equals y2, it's a horizontal line. <br>
When x1 equals x2, its a vertical line.
</solution>
</details>

## Shape 3 - triangle

Syntax:

```
triangle(x1, y1, x2, y2, x3, y3); //draws triangle with the three corners at (x1, y1), (x2, y2) and (x3, y3)
```

Example:

```
triangle(20, 80, 50, 40, 10, 70); //triangle with corners at (20, 80), (50, 40) and (10, 70)
```

## Shape 4 - circle

Syntax:

```
circle(x, y, dia); //draws a circle with centre at (x, y) and diameter of dia
```

Example:

```
circle(60, 40, 70); //circle centred at (60, 40) with 70 diameter.
```

## Shape 5 - square

Syntax:

```
square(x, y, len); //draws a square with TOP-LEFT CORNER at (x, y) and sides of len length
```

Example:

```
square(60, 40, 70); //square with TOP-LEFT CORNER at (60, 40) with each side 70 pixels.
```

## Shape 6 - rect

Syntax:

```
rect(x, y, lenX, lenY); //draws a rectangle with TOP-LEFT CORNER at (x, y) and breadth of lenX, and height of lenY.
```

Example:

```
rect(60, 40, 70, 50); //rectangle with TOP-LEFT CORNER at (60, 40) with breadth of 70 and height of 50.
```

## Things I don't discuss

- `ellipse`
- `arc`
- `bezier`
- `rectMode`
- `ellipseMode`.
- `beginShape`.







