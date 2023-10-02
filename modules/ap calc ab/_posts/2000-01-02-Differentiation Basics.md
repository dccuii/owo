# Topic 2: Differentiation Basics

This topic discusses the basics of differentiation as well as various techniques to find the derivative of different functions. 

There is a pretty heavy reliance of the use of 3Blue1Brown's series, [Essence of Calculus](https://youtube.com/playlist?list=PLZHQObOWTQDMsr9K-rj53DwVRMYO3t5Yr&si=1gvWlAfEUFH_VdDm), on YouTube. Many thanks to his incredible videos! I genuinely cannot explain as well as he can for some of these topics. His work is incredible. 

Sections in this unit: 
- 2.1: Derivative definition and basic rules
- 2.2: Product and quotient rule
- 2.3: Trig function derivatives
- 2.4: Chain rule
- 2.5: Implicit differentiation
- 2.6: Inverse functions
- 2.7: Inverse trig functions

---
## 2.1: Derivative definition and basic rules

The concept of the derivative distinctly comes before the concept of the integral, yet the analysis of integrals requires the understanding of derivatives. Therefore, despite the backwards approach of the order of what topics we learn first, at least the idea of derivatives and what it means, graphically, is fundamental to learn. 

The shortening of an interval over which we calculate the average rate of change is the key to understanding *instantaneous slope*, in other words, the slope of the tangent line of a graph at a certain point. 

The definition of a function limit is as follows:
$$ f'(x) = \lim_{h \rightarrow 0} \frac{f(x+h) - f(x)}{h}. $$

The derivative of $f(x)$ at $x=c$, or $f'(c)$, is defined as follows:
$$ f'(c) = \lim_{x \rightarrow c} \frac{f(x)-f(c)}{x-c}. $$

The derivative at a point gives rise to a very important property about derivatives. Not only does the point have to be defined for the derivative to exist (lol obv), the two one-sided limits *also* have to exist. This *is* the limit definition. Thus if the two one-sided limits are unequal, then the derivative *cannot* exist. 

In this section, we look at the derivatives of: 
- constant functions 
- straight lines
- monomials/polynomials
- sin and cos
- the exponential function

There are also many different ways to notate the derivative:
- $f'(x)$
- $f'$
- $\frac{dy}{dx}$
- $y'$
- $(f(x))'$

## 2.2: Product and quotient rule

Self explanatory, we look at the product and quotient rule. These are things that you more or less have to memorize for right now, since proofs are beyond the AP exam. 

However, we use these rules to analyze the derivatives of other trigonometric functions, like tan, cot, sec, and csc. 

## 2.4: Chain rule

First, the rule: 
$$ [f(g(x))]' = f'(g(x))*g'(x)$$

alr this is a confusing one, im gonna speak a bit more informally here

so like yknow when 3b1b talked about this idea of changing the value of $x$ and seeing how much $y$ changed ($dy = f'(x) * dx$) a very similar idea can be applied here. 

first, the no-chain-rule analysis: we have some $dx$. the corresponding change in $y$, $dy$, is "proportional" to $dx$ by a factor of $f'(x)$. This is literally what $\frac{dy}{dx} = f'(x)$ means, it's just rewritten.

in other words, if we change $x$, the change in $y$ is not always one-to-one. it depends on something, *the derivative*, to alter that change to accurately describe the change in $y$ that occurs. 

now, the chain rule part. rearranging, we get $dy = f(u) * du = f'(g(x)) * g'(x) * dx$. the $u$ part says that we can treat $g(x)$ like its own input variable, and the same logic applies to the above paragraphs. however, $g(x)$ also depends on $x$. so $d[f(g(x))]$ depends on $g(x)$, and $du = d[g(x)]$ depends on $x$. 

so, finally, for $f(g(x))$, if we change $dx$, our corresponding change in $y$ is based on, firstly, how $g(x)$ changes the output of $f(x)$ (this is the $g'(x)$ part), and then secondly, how $f(g(x))$ changes $y$'s output. that's the $f'(g(x))$ part, and also why the inside of $f'$ is $g(x)$ and not $g'(x)$. 

ok i hope that made sense

## 2.5: Implicit differentiation

## 2.6: Inverse functions

## 2.7: Inverse trig functions