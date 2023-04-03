
x = (1−t)2x1 + 2(1−t)tx2 + t2x3
y = (1−t)2y1 + 2(1−t)ty2 + t2y3
Instead of x1, y1, x2, y2, x3, y3 we should put coordinates of 3 control points, and then as t moves from 0 to 1, for each value of t we’ll have (x,y) of the curve.



For instance, if control points are (0,0), (0.5, 1) and (1, 0), the equations become:



x = (1−t)2 0 + 2(1−t)t 0.5 + t2 * 1 = (1-t)t + t2 = t
y = (1−t)2 0 + 2(1−t)t 1 + t2 * 0 = 2(1-t)t = –2t2 + 2t
Now as t runs from 0 to 1, the set of values (x,y) for each t forms the curve for such control points.
