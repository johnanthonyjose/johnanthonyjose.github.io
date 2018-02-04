---
subheadline: In-Class Problem
title: 'Path in Curvilinear Coordinates'
mathjax: true
---
Curvilinear Problem Example 2

A car starts from rest at point A and increases its speed at a constant rate as it enters a curve. The magnitude of the total acceleration of the car as it passes point B, which is $$\frac{400}{3}  m$$ along the curve from point A, is $$2.5 \frac{m}{s^2}$$. The radius of curvature at point B is 200 m.

a.) Determine the normal and tangential components of the acceleration at point B [*Answer>>*](#ans1)

b.) If the tangential acceleration at point B is directed downward to the right at an angle of $$36.87^\circ$$ below the horizontal and the normal acceleration is also directed downward, determine the rectangular components of the acceleration at point B. [*Answer>>*](#ans2)

<!--more-->

# SOLUTION:

## Step 1: Draw

Just like in any of our problems, we try to visualize first the problem before solving it.

<img class="center" src="https://docs.google.com/drawings/d/e/2PACX-1vQjMbD73j9_KiMmq7oeWGkKOHhUWTXvCP4fZF1IKf26vEeqDEP0bt6rzIcLKrOW7Do1V7H5vZ6DG71w/pub?w=470&h=275">

## Step 2: Write the Problem

1. normal acceleration, $a_{N}$

2. tangential acceleration, $a_{tan}$

## Step 3: Guess
The first thing you wanna ask yourself is: what are some equations do I know given the problem?

For me, the first equation I can think of is:

$$ a_{total}^{2} = a_{tan}^{2} + a_{N}^{2} $$

at point B,

<div>
$$
   \begin{equation} 
      2.5^{2} = a_{tan}^{2} + a_{N}^{2}
   \end{equation}
$$
</div>

After writing equation above, I'm stuck. But, when I think about it, I haven't utilized all the given values:

Recall if I could just imagine bending the curved path into a straight line[put image], then, perhaps, I could the constant acceleration equations I've previously known.

$$ v = v_{o} + at$$

$$ v^2 = v_{o}^2 + 2a\Delta s $$

$$ s = s_{0} + v_ot + \frac{1}{2}at^2 $$ 

Caveat: the acceleration to be used should be the acceleration along the curve.Hence, tangential acceleration [more info][1]

As the time is not given, the most logical first equation is:

$$ v^2 = v_{o}^2 + 2a_{tan}\Delta s $$

We set the point A as the initial point and point B as the final point, hence:

<div>
$$
   \begin{equation} 
      v^2 = 0 + 2a_{tan} \left( \frac{400}{3} \right)
   \end{equation}
$$
</div>

We have one more given that we haven't utilized, radius of curvature at point B. It might be:

$$ a_{N} = \frac{v^2}{\rho} $$

<div>
$$
   \begin{equation} 
      a_{N} = \frac{v^2}{200}
   \end{equation}
$$
</div>

Substitute equation (3) to (2), we get

$$ 200 a_{N} = 2a_{tan} \left( \frac{400}{3} \right) $$

<div id="ans1">
$$
   \begin{equation} 
      a_{N} = \left( \frac{4}{3} \right) a_{tan} 
   \end{equation}
$$
</div>

Substituting equation (4) to (1),

$$ 2.5^{2} = a_{tan}^{2} + \left(\frac{4}{3} a_{tan} \right)^2 $$

from here we get,

$$ a_{tan} = 1.5 \frac{m}{s^2}$$

Using equation (1) and solving for $a_{N}$,

$$ 2.5^{2} = 1.5^2 + a_{N}^{2} $$

$$ a_{N} = 2.0 \frac{m}{s^2} $$


## Step 4: Check if all problems are met
No, as we still have to solve b.

## Step 4.1: Visualize
<img class="center" src="https://docs.google.com/drawings/d/e/2PACX-1vRk49nMjsdy_rYC6BnaNh92lW-OtRwLCWbN5_PBR561AvDXILSCfgA_nHMQMYAbFxYD9efX3HRbyM9o/pub?w=470&amp;h=275">

## Step 4.2: write the problem
$$ \vec{a_{x}}, \vec{a_{y}} $$

## Step 4.3: Guess
Just by looking at the diagram above, it seems that what we need to do is to break down the tangential component $a_{tan}$ into its x- and y-component. Similarly, do the same procedure with the normal component

By inspection,

$$ \vec{a_{tan}} = |\vec{a_{tan}}|\cos(-38.2^\circ) \hat{\imath} + |\vec{a_{tan}}|\sin(-38.2^\circ) \hat{\jmath} $$ 

Note: $\cos(-\theta) = \cos(\theta)$ and $\sin(-\theta) = \sin(\theta) $, 

$$ \vec{a_{tan}} = |\vec{a_{tan}}|\cos(38.2^\circ) \hat{\imath} - |\vec{a_{tan}}|\sin(38.2^\circ) \hat{\jmath} $$ 

<div>
$$
   \begin{equation} 
      \vec{a_{tan}} = 1.5\cos(38.2^\circ) \hat{\imath} - 1.5\sin(38.2^\circ) \hat{\jmath}
   \end{equation}
$$
</div>


For the normal component $\vec{a_{N}}$,<br  />
By visual inspection,

$$ \vec{a_{N}} = -|\vec{a_{N}}|\cos(38.2^\circ) \hat{\imath} - |\vec{a_{N}}|\sin(38.2^\circ) \hat{\jmath} $$ 

<div>
$$
   \begin{equation} 
      \vec{a_{N}} = -2.0\cos(38.2^\circ) \hat{\imath} - 2.0\sin(38.2^\circ) \hat{\jmath}
   \end{equation}
$$
</div>


So, to get the $a_{x}$ we simply get the sum of the x-components of equation (5) and (6),

<div id="ans2">
$$ 
    \begin{array}{lcl}
        a_{x} & = & a_{tan_{x}} + a_{N_{x}} \\ 
              & = & 1.5\cos(38.2^\circ) + -2.0\cos(38.2^\circ) \\
              & = & -0.392928 \frac{m}{s^2}
    \end{array}
$$
</div>

Similarly,
<div>
$$ 
    \begin{array}{lcl}
        a_{y} & = & a_{tan_{y}} + a_{N_{y}} \\ 
              & = & -1.5\sin(38.2^\circ) + - 2.0\sin(38.2^\circ) \\
              & = & -2.164 \frac{m}{s^2}
    \end{array}
$$
</div>

[1]: http://example.com

