---
layout: page
title: Coordinate System
within: programming
---

<details class="prereq" markdown="1"><summary>Assumed Knowledge</summary>

<!--  * <a href="./lists">Lists</a>
  * <a href="./loops">Loops</a>-->
</details>

<details class="outcomes" markdown="1"><summary>Learning Outcomes</summary>
  * Learning about Processing coordinate system.
</details>

## Author: Gaurav Gupta

<a href="./ProcessingLesson1.pdf">Processing Lesson 1</a>

All locations in Processing are measured from the top-left corner. We call this the origin.

Each location in processing is given by a pair of two numbers, x and y.

The first number represents how far RIGHT, from the top-left corner, is the point.

The second number represents how much further DOWN, from the top-left corner, is the point.

For example, 

- (40, 30) represents a point that is 40 pixels to the right, and 30 pixels below the top-left corner.


You can determine a point by first going x pixels to the right, and then y pixels down.

To determine where (80, 50) will be,

- first go 80 pixels to the right of the top-left corner.
- then go 50 pixels down from there.

## Size

The default size of a Processing sketch is 100 by 100. The top-left point is (0, 0) and the bottom-right point is (99, 99).

You can change the size by using,

```
size(width, height);
```

For example,

```
size(600, 400);
```

will result in a sketch that is 600 pixels wide and 400 pixles high.

## Activities

- Create a Processing sketch that is 400 pixels in width and twice as much in height.
- Create a Processing sketch that is 600 pixels in width and a third of that in height.
- Create a square Processing sketch that is 300 pixels in width.
- Plot the following points for a Processing sketch that is 300 by 300:
	-1 	