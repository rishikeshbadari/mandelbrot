# my notes

I took a class at GHP some years ago where we wrote some basic stuff to visualize the Mandelbrot set. 

I was bored this summer and couldn't remember how it was constructed, so these are just some notes.

## definition
Back when I took the class, I thought fractals were just self-similar shapes. You zoom in enough and eventually see the same thing. Apparently, that's not the case, and according to [3Blue1Brown](https://www.youtube.com/watch?v=gB9n2gHsHN4), we can define fractals more rigorously.

Some other definitions help with defining fractals. 

<strong>Scaling Factor:</strong> I was actually having trouble defining this well. I'm sure one of these will suffice:

Given two similar shapes (similar as in the math definition of the word): 
1. Choose the same curve/side on both shapes and take its length. Divide the larger length by the smaller length to find the factor to scale from the smaller to the larger shape. 1 over that to scale down.
2. Lay one of the shapes on the plane. If you multiply all points on the shape by some factor $s$, the resulting shape will be congruent to the other shape. That's the scaling factor from the one you laid down to the other one.

<strong>Mass: </strong> I guess area in a way. Some fractals are technically just a lot of lines (Sierpinski Triangle), so thinking of it as if you were measuring grams is actually better.


<strong>Dimension: </strong> Also not easy to define. Someone on Wolfram MathWorld says it's 'the number of coordinates needed to specify a point on the object'. Doesn't make much sense in terms of non-integer values for fractals.

Easier to observe in practice:

1. If we scale a line segment by $\frac{1}{2}$, its mass scales by $\Big(\frac{1}{2}\Big)^1$.
2. If we scale a square by $\frac{1}{2}$, its mass scales by $\Big(\frac{1}{2}\Big)^2$.
3. If we scale a cube by $\frac{1}{2}$, its mass scales by $\Big(\frac{1}{2}\Big)^3$.

Therefore, it seems to follow that if we scale a shape by $s$ and its mass scales by $s^d$, the shape's dimension is $d$.

Given all that, a <strong>Fractal</strong> is a shape with non-integer dimension. 

## fractals

visit each branch
