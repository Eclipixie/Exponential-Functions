# Derivation Rules

## Chain Rule

Used when there is a function of a function, e.g.

$$y=\sqrt{25-x^2}$$

This can be split into $y=\sqrt{u}$ where $u=25-x^2$.

The chain rule can be defined as:

* $y=f(x)$ then $\frac{dy}{dx}=\frac{dy}{du}\cdot\frac{du}{dx}$
	* Differentiating $y$ with respect to $u$ multiplied by differentiating $u$ with respect to $x$
* $y=g(f(x))$ then $\frac{dy}{dx}=f'(x)\cdot g'(f(x))$

For polynomials:

$$y=f(x)^n$$

$$\frac{dy}{dx}=n(f(x))^{n-1}\cdot f'(x)$$

## Product Rule

Suppose $y=u\cdot v$ where $u$ and $v$ are both functions of $x$. $\therefore y=u(x)\cdot v(x)$

Then:

$$\frac{dy}{dx}=v\frac{du}{dx}+u\frac{dv}{dx}$$

or:

$$\frac{dy}{dx}=v(x)u'(x)+u(x)v'(x)$$

## Quotient Rule

if $f(x)=\frac{u(x)}{v(x)}$ then

$$f'(x)=\frac{v(x)u'(x)-u(x)v'(x)}{v(x)^2}$$

or $y=\frac{u}{v}$ then

$$\frac{dy}{dx}=\frac{v\frac{du}{dx}-u\frac{dv}{dx}}{v^2}$$
