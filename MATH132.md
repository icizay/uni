
This notes start from 14.5 after directional derivatives, Thomas Calculus.

30th May 2025.

Chapter 14.5

---

**Gradient vector (gradient)** of f(x, y) at a point P_0(x_0, y_0) is the **vector**:

$$\nabla f = \frac{\partial f}{\partial x} \bold{i} + \frac{\partial f}{\partial y}\bold{j}$$

  

**The directional derivative is a dot product**

If f(x, y) is differentiable in an open region containing P_0(x_0, y_0) then

$$\bigg(\frac{df}{ds}\bigg)_{\bold{u},\space P_0} = (\nabla f)_{P_0} \cdot  \bold{u}$$

$$D_{\bold{u}}f = \nabla f \cdot  \bold{u} = |\nabla f|\cos\theta$$

  

**Properties**

  

$f$ increases most rapidly in the direction of the gradient vector $\nabla f$ at $P$. Likewise, it decreases most rapidly in the direction of $-\nabla f$.

  

Any direction $\bold{u}$ orthogonal to a gradient $\nabla f \neq0$ is a direction of **zero change**. $\cos(\pi/2)= 0$

  

This properties hold in three dimensions as well as two.

  

**Gradients and Tangents to Level Curves**

At every point $(x_0, y_0)$ in the domain of a differentiable function $f(x,y)$, the gradient of $f$, $(\nabla f)$ is normal to the level curve through $(x_0, y_0)$.

  

**Tangent Line to a Level Curve**

The tangent line is normal to gradient of a level curve.

For a point $P_0 = (x_0, y_0)$

$$ f_x(x_0,y_0)(x - x_0) + f_y(x_0, y_0)(y - y_0) = 0$$

  

**Algebra Rules for Gradients**

$+, -$ and constant multiple have trivial rules.

**Product Rule**

$$\nabla (fg) = f\nabla g + g\nabla f$$**Quotient Rule**

$$\nabla  \bigg(\frac{f}{g}\bigg) = \frac{g\nabla f-f\nabla{g}}{g^2}$$

**Scalar multipliers** on left of gradients.

  

For **3D**, calculating gradients and directional derivative is same. And the properties listed earlier also apply here.

  

**The Derivative along a path**

$$\frac{d}{dt}f(r(t)) = \nabla f(r(t)) \cdot r'(t)$$

  

**Chapter 14.6**
---
All the velocity vectors at $P_0$ are orthogonal to $\nabla f$ at $P_0$, so the curves' tangent lines all lie in the plane through $P_0$ normal to $\nabla f$.

Tangent plane is a plane where we take normal as $\nabla F$.

**Tangent plane to $f(x,y,z) = c$ at $P_0(x_0,y_0,z_0)$**
$$f_x(P_0)(x - x_0) + f_y(P_0)(y-y_0)+f_z(P_0)(z-z_0) = 0$$
**Normal line to $f(x,y,z) = c$ at $P_0(x_0,y_0,z_0)$**
$$\ell(t)= (x_0, y_0, z_0) + t\cdot\nabla f_{P_0}$$

**Plane tangent to a Surface $z = f(x, y)$ at $(x_0, y_0, f(x_0, y_0))$**
$$f_x(P_0)(x - x_0) + f_y(P_0)(y-y_0) = z- z_0$$ This comes from the fact that 
$$0 = - z +  f(x, y)$$then 
$$f_z(x,y) = -1$$

To rotate a vector $(a, b)$ counterclockwise you do $(-b, a)$.

**Estimating the Change in $f$ in a Direction $\mathrm{u}$**
To estimate the change in the value of a differentiable function $f$ when we move a small distance $ds$ form a point $P_0$ in a particular direction $\bold u$, use the formula:
$$df = (\nabla f|_{P_0} \cdot \bold u)\space ds$$

**How to linearize a function of two variables?**
We wish to approximate $z = f(x, y)$ near a point $P_0$ which we know values of $f$, $f_x$, $f_y$ and f is differentiable. If we move from $P_0$ to any nearby point $P$ by increments $\Delta x = x - x_0$ and $\Delta y = y - y_0$, then the change is:
$$f(x, y) - f(x_0, y_0) = f_x(x_0, y_0)\Delta x + f_y(x_0, y_0)\Delta y + \epsilon_1\Delta x + \epsilon_2 \Delta y$$
where $\epsilon_1, \epsilon_2 \rightarrow 0$ as $\Delta x, \Delta y \rightarrow 0$, if the increments are small, the product will be smaller and we have the approximation:
$$L(x, y) = f(x, y) \approx f(x_0, y_0) + f_x(x_0, y_0)(x - x_0) + f_y(x_0, y_0)(y - y_0)$$
**Error in Standard Linear Approximation**
If $f$ has continuous first and second partial derivatives throughout an open set containing a rectangle $R$ centered at $P_0$ and if M is any upper bound for the values of $|f_{xx}|, |f_{yy}|, |f_{xy}|$ on $R$, then the error $E(x, y)$ incurred in replacing $f(x, y)$ on $R$ by its linearization satisfies the inequality
$$|E(x, y)| \leq \frac{1}{2}M(|x - x_0| + |y - y_0|)^2$$
To make $|E(x, y)|$ small for a given M, we just make $|x - x_0|$ and $|y - y_0|$ small.

**Differentials**
If we move from $P_0$ to $P_0 + (dx, dy)$ nearby, the resulting change
$$df = f_x(P_0)dx + f_y(P_0)dy$$
in the linearization of $f$ is called the **total differential of $f$**

**for More than two variables**
$$L(x, y, z) = f(x, y, z) \approx f(x_0, y_0, z_0) + f_x(x_0, y_0, z_0)(x - x_0) + f_y(x_0, y_0, z_0)(y - y_0) + f_z(x_0, y_0, z_0)(z - z_0)$$

Suppose that R is a closed rectangular solid centered at $P_0$ and lying in an open region on which the second partial derivatibes of $f$ are continuous. Suppose also that $|f_{xx}|, |f_{yy}|, |f_{zz}|, |f_{xy}|, |f_{xz}|, |f_{yz}|$ are all less than or equal to $M$ throughout $R$. Then the **error** $E(x, y, z) = f(x, y, z) - L(x, y, z)$ in the approximation of $f$ by $L$ is bounded throughout $R$ by the inequality
$$|E| \leq \frac{1}{2}M(|x - x_0| + |y - y_0| + |z - z_0|)^2$$
and if the second partial derivatives of $f$ are continuous and if $x, y$ and $z$ change from $P_0$ by small amounts $dx, dy$ and $dz$, the **total differential**
$$df = f_x(P_0)dx + f_y(P_0)dy + f_z(P_0)dz$$ gives a good approximation of the resulting change in $f$.

Chapter 14.7
----
**Derivative tests for Local Extreme Values**
$f(a,b)$ is a **local minimum** value of $f$ if $f(a, b) \leq f(x, y)$ for all domain points $(x, y)$ in an open disk centered at $(a, b)$. Similar for **local maximum**.

At such points the tangent planes, when they exist, are **horizontal**. Local extrema are also called **relative extrema**.

**First derivative test** is: If $f(x, y)$ has a local maximum or minimum value at an interior point $(a, b)$ of its domain and if the first partial derivatives exist there, then $f_x(a, b)  = 0$ and $f_y(a, b)$ = 0.

Important!
An interior point of the domain of a function $f(x, y)$ where both $f_x, f_y$ are zero or where one or both of $f_x, f_y$ do not exist is a **critical point!** of $f$.

Like a differentiable function of a single variable might have a point of inflection. A differentiable function of two variables might have a **saddle point**, with the graph of **f** crossing the tangent plane defined there.

A differentiable function has a **saddle point** at a critical point $(a, b)$ if in every open disk centered at $(a, b)$ there are domain points $(x, y)$ where $f(x, y) > f(a, b)$ and $f(x, y) < f(a, b)$. The corresponding point $(a, b, f(a, b))$ on the surface $z = f(x, y)$ is called a saddle point on the surface.

**Second Derivative Test for Local Extreme Values**
If $f(x, y)$ and its first and second partial derivatives are continuous throughout a disk centered at $(a, b)$ and $f_x(a, b) = f_y(a, b) = 0$, then:
$f$ has a **local maximum** at $(a, b)$ if $f_{xx} < 0$ and $f_{xx}f_{yy} - f_{xy}^2 > 0$ at $(a, b)$
$f$ has a **local minimum** at $(a, b)$ if $f_{xx} > 0$ and $f_{xx}f_{yy} - f_{xy}^2 > 0$ at $(a, b)$
$f$ has a **saddle point** at $(a, b)$ if $f_{xx}f_{yy} - f_{xy}^2 < 0$ at $(a, b)$
**The test is inconclusive** at $(a, b) if $f_{xx}f_{yy} - f_{xy}^2 = 0$ at $(a, b)$. In this case we must find some other way to determine the behavior of f at $(a, b)$.
The expression $f_{xx}f_{yy} - f_{xy}^2$ is called the **discriminant** or **Hessian** of $f$.
$$f_{xx}f_{yy} - f_{xy}^2 = \begin{vmatrix}  
f_{xx} & f_{xy} \\  
f_{xy} & f_{yy}  
\end{vmatrix}$$

In summary, if $\mathrm{Hess}(f) > 0$ at $(a, b)$ then the surface curves the same way in all directions: downward if $f_{xx} < 0$ giving rise to a **local maximum**, upward if $f_{xx} > 0$ giving a **local minimum**

On the other hand if $\mathrm{Hess}(f) < 0$ at $(a, b)$ then the surface curves are up in some directions and down in others, so we have a **saddle point**.

**Absolute Maxima and Minima on Closed Bounded Regions**
For a continuous function $f(x, y)$ on a closed and bounded region R to find absolute extrema we:
1- *List the interior points* of $R$ where $f$ may have local extrema and evaluate $f$ at the points. These are critical points of $f$.
2- *List the boundary points* of $R$ where $f$ local extrema.
3- *Look through the lists* for the max/min values of $f$.

!! *Solving extreme value problems with algebraic constraints on the variables usually requires the method of **Lagrange multipliers** introduced in the next section.*

This theorem does not apply to **boundary points** of a function's domain--but it is possible for a function have extreme values along with *nonzero derivatives*, also it does not apply to points where either $f_x$ or $f_y$ fails to exist.

Given a plane
$Ax + By + Cz + D = 0$
and a point $P_0$
the **perpendicular (shortest) distance** from the point to the plane is:
$$ = \frac{|A x_0 + B y_0 + C z_0 + D|}{\sqrt{A^2 + B^2 + C^2}}$$
from projection of a vector $\vec{v}$ on a plane to the normal of the plane 
$$\text{proj}_{\vec{n}} \vec{v} = \frac{\vec{v} \cdot \vec{n}}{|\vec{n}|}$$

**Lagrange Multipliers**
 Local extreme values of a function $f(x, y, z)$ whose variables are subject to a constraint $g(x, y, z) = 0$ are to be found on the surface $g = 0$ among the points where
 $$\nabla f = \lambda \nabla g$$ for some scalar $\lambda$, called a **Lagrange multiplier**

**The Orthogonal Gradient Theorem**
Suppose that $f(x, y, z)$ is differentiable in a region whose interior whose interior contains a smooth curve
$$C: \bold r(t) = x(t)\bold i + y(t) \bold j + z(t) \bold k$$
if $P_0$ is a point on $C$ where $f$ has a local maximum or minimum relative to its values on $C$ then $\nabla f$ is orthogonal to $C$ at $P_0$.

**The Method of Lagrange Multipliers**
Suppose that $ƒ(x, y, z)$ and $g(x, y, z)$ are differentiable and $\nabla g ≠ 0$ when $g(x, y, z) = 0$. To find the local maximum and minimum values of ƒ subject to the constraint $g(x, y, z) = 0$ (if these exist), find the values of $x, y, z$ and $\lambda$ that simultaneously satisfy the equations 
$$\nabla f = \lambda \nabla g$$ 
and
$$g(x, y, z) = 0$$
 For functions of two independent variables, the condition is similar, but without the variable z.

**Lagrange Multipliers with Two Constraints**
If the constraints are $g_1(x, y, z) = 0$ and $g_2(x, y, z) = 0$ and $g_1$ and $g_2$ are differentiable, with $\nabla g_1$ not paralel to $\nabla g_2$, we find the constrained local maxima and minima of $f$ by introducing two Lagrange multipliers with $\lambda$ and $\mu$.
$$\boxed{\nabla f = \lambda \nabla g_1 + \mu \nabla g_2}$$ $$\boxed{g_1(x, y, z) = 0}$$$$\boxed{g_2(x, y, z) = 0}$$

**14.9 Taylor's Formula for Two Variables**
not included in syllabus, check later though

Chapter 15
----
**Multiple Integrals**
General idea is similar to Riemann integrals for one variable, but it requires thinking to understand, I didn't yet.

**Fubini's Theorem (First Form)**
If $f(x, y)$ is continuous throughout the rectangular region $R: a \leq x \leq b, c \leq y \leq d$, then
$$\underset{R}\iint{f(x, y)\space dA} = \int_{c}^{d}\int_{a}^{b}f(x,y)\space dx\space dy = \int_{b}^{a}\int_{d}^{c}f(x,y)\space dy\space dx$$

**Double Integrals over General Regions**

**Fubini's Theorem (Stronger Form)**
Let $f(x, y)$ be continuous on a region $R$.
1- If $R$ is defined by $a \leq x \leq b, g_1(x) \leq y \leq g_2(x)$ with $g_1$ and $g_2$ continuous on $[a, b]$, then
$$\underset{R}\iint{f(x, y)\space dA = \int_b^a \int_{g_1(x)}^{g_2(x)}f(x, y)dy \space dx}$$
2- If $R$ is defined by $c \leq y \leq d, h_1(y) \leq x \leq h_2(y)$ with $h_1$ and $h_2$ continuous on $[c, d]$, then
$$\underset{R}\iint{f(x, y)\space dA = \int_c^d \int_{h_1(x)}^{h_2(x)}f(x, y)dx \space dy}$$

If you slice **vertically** integrate **y** first. For each fixed $x$, you walk from $y = c$ to $y = d$ mesauring the height $f(x, y)$ above as you go. Then you sum up this "vertical strip" (area under the curve for fixed. Then you take $x + dx$ covering $[a, b]$.
Then it is $dydx$

**15.3 Area by Double Integration**
If we take $f(x, y) = 1$, then we find the area of a closed, bounded plane region R:
$$A = \underset{R}\iint dA$$
If we wish to find the average of a function, we simply total volume by the area, thus
Average value of $f$ over $R$:
$$= \frac{1}{A} \underset{R}\iint{fdA}$$

Chapter 11
--

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTQ2MTExNTkzNiwtMTkxMDI1MjM4OSwtNj
cxODUzODY5LDEwODI5NDEzMjcsLTEyOTMwMDMyNTgsNTA0MDAy
MTUyLC00NzY1MTY1OCwtNzAwODY3NDc5LDU2MjYxNDE1LDI5OT
I4NjkzNyw1OTI1Nzc5NzEsLTE0MTI3ODY1NTNdfQ==
-->