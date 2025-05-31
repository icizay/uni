This notes start from 14.5 after directional derivatives, Thomas Calculus.
 30th May 2025.
 
Chapter 14.5
---
**Gradient vector (gradient)** of f(x, y) at a point P_0(x_0, y_0) is the **vector**:
$$\nabla f = \frac{\partial f}{\partial x} \bold{i} + \frac{\partial f}{\partial y}\bold{j}$$

**The directional derivative is a dot product**
If f(x, y) is differentiable in an open region containing P_0(x_0, y_0) then
$$\bigg(\frac{df}{ds}\bigg)_{\bold{u},\space P_0} = (\nabla f)_{P_0} \cdot \bold{u}$$
$$D_{\bold{u}}f = \nabla f \cdot \bold{u} = |\nabla f|\cos\theta$$

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
$$\nabla \bigg(\frac{f}{g}\bigg) = \frac{g\nabla f-f\nabla{g}}{g^2}$$
**Scalar multipliers** on left of gradients.

For **3D**, calculating gradients and directional derivative is same. And the properties listed earlier also apply here.

**The Derivative along a path**
$$\frac{d}{dt}f(r(t)) = \nabla f(r(t)) \cdot r'(t)$$

**Chapter 14.6**
---




<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE0MTI3ODY1NTNdfQ==
-->