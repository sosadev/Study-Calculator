# Study Time Calculator

## Equation

Start with a negative exponential equation plus 6 to account for the exponential decrease.

$$
f(x)=-a^t + 6
$$

I want to be able to calculate study time necessary up to 10 days prior to the assessment, so I will plug 10 into the x and solve for a.

$f(x) = -a^{10} + 6$

$-6 = -a^{10}$

$6 = a^{10}$

$a=\sqrt[10]{6}$

$$
f(x)=-\left(\sqrt[10]{6}\right)^{t}+6
$$

I wanted to incorporate the difficulty of a course into the calculation, so I multiplied the equation by ${6}/{5}d$.

$$
f\left(x\right)=\left(\frac{6}{5}d\right)\left(-\left(\sqrt[10]{6}\right)^{t}+6\right)\left\{0<x\right\}
$$

I decided to also incorporate the user’s course average by dividing  $6/5d$ by $a - 3/20$.

This gave me the final equation:

$$
f\left(x\right)=\left(\frac{\left(\frac{6}{5}d\right)}{a-\frac{3}{20}}\right)\left(-\left(\sqrt[10]{6}\right)^{t}+6\right)
$$

## The Code