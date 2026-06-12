---
title: Derivatives
subject: mathematics
section: Calculus
order: 1
description: Definition of the derivative and basic rules.
---

## Definition

The derivative of $f$ at $x$ is the limit of the difference quotient:

$$
f'(x) = \lim_{h \to 0} \frac{f(x+h) - f(x)}{h}
$$

## Basic rules

| Rule | Formula |
| --- | --- |
| Power | $\frac{d}{dx} x^n = n x^{n-1}$ |
| Product | $(fg)' = f'g + fg'$ |
| Chain | $(f \circ g)'(x) = f'(g(x))\, g'(x)$ |

## Example

Differentiate $f(x) = x^2 \sin x$ using the product rule:

$$
f'(x) = 2x \sin x + x^2 \cos x
$$
