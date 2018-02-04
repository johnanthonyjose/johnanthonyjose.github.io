---
subheadline: In-Class Problem
title: 'Path in Curvilinear Coordinates'
mathjax: true
---
Curvilinear Problem Example 2

A car starts from rest at point A and increases its speed at a constant rate as it enters a curve. The magnitude of the total acceleration of the car as it passes point B, which is $$\frac{400}{3}  m$$ along the curve from point A, is $$2.5 \frac{m}{s^2}$$. The radius of curvature at point B is 200 m.

a.) Determine the normal and tangential components of the acceleration at point B

b.) If the tangential acceleration at point B is directed downward to the right at an angle of $$36.87^\circ$$ below the horizontal and the normal acceleration is also directed downward, determine the rectangular components of the acceleration at point B.

<!--more-->

**SOLUTION:**

***Step 1: Draw***

Just like in any of our problems, we try to visualize first the problem before solving it.

<img class="center" src="https://docs.google.com/drawings/d/e/2PACX-1vQjMbD73j9_KiMmq7oeWGkKOHhUWTXvCP4fZF1IKf26vEeqDEP0bt6rzIcLKrOW7Do1V7H5vZ6DG71w/pub?w=470&h=275">

***Step 2: Write the Problem***
a.)
normal acceleration, $$a_{normal}$$
tangential acceleration, $$a_{tan}$$

****Step 3: Guess****
The first thing you wanna ask yourself is: what are some equations do I know given the problem?

For me, the first equation I can think of is:

$$ a_{total}^{2} = a_{tan}^{2} + a_{normal}^{2} $$

at point B,

$$ 2.5^{2} = a_{tan}^{2} + a_{normal}^{2} $$

After writing equation above, I'm stuck. But, when I think about it, I haven't utilized all the given values:

Recall if I could just imagine bending the curved path into a straight line[put image], then, perhaps, I could the constant acceleration equations I've previously known.

$$ V = V_{o} + at$$

$$ V^2 = V_{o}^2 + 2a\Delta s $$

$$ s = s_{0} + V_ot + \frac{1}{2}at^2 $$ 

Caveat: the acceleration to be used should be the acceleration along the curve.Hence, tangential acceleration more info: [see this link][1]

As the time is not given, the most logical first equation is:

$$ V^2 = V_{o}^2 + 2a_{tan}\Delta s $$

We set the point A as the initial point and point B as the final point, hence:

$$ V^2 = 0 + 2a_{tan} (\frac{400}{3}) $$

We have one more given that we haven't utilized, radius of curvature at point B. It might be:

<span>
$$\begin{array}{lcl} a_{normal} & = & \frac{v^2}{\rho} \nonumber \\ a_{normal} & = & \frac{v^2}{200} \nonumber \end{array}$$
</span>

$$
\begin{align*}
  & \phi(x,y) = \phi \left(\sum_{i=1}^n x_ie_i, \sum_{j=1}^n y_je_j \right)
  = \sum_{i=1}^n \sum_{j=1}^n x_i y_j \phi(e_i, e_j) = \\
  & (x_1, \ldots, x_n) \left( \begin{array}{ccc}
      \phi(e_1, e_1) & \cdots & \phi(e_1, e_n) \\
      \vdots & \ddots & \vdots \\
      \phi(e_n, e_1) & \cdots & \phi(e_n, e_n)
    \end{array} \right)
  \left( \begin{array}{c}
      y_1 \\
      \vdots \\
      y_n
    \end{array} \right)
\end{align*}
$$


[1]: http://example.com

