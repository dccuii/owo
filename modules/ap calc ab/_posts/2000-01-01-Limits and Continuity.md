# Topic 1: Limits and Continuity

This topic discusses limits and continuity. This topic, but especially the concept of the limit, is the foundation of the entirety of calculus. 

Sections in this unit: 
- 1.1: Limit definition and estimation
- 1.2: Limit evaluation
- 1.3: Squeeze theorem
- 1.4: Continuity and discontinuity
- 1.5: Intermediate value theorem
- 1.6: Asymptotes

---
## 1.1: Limit definition and estimation

This section discusses the limit notation, $\lim_{x \rightarrow c} f(x) = L$, as well as understanding what the limit means intuitively. We look at two different ways to estimate the limit: visually using a graph, and also using a table of $x$ values that approach the limit point, $c$. 

$\lim_{x \rightarrow c} f(x) = L$, in words, is "the limit of $f(x)$ as $x$ approaches $c$ is $L$. Intuitively, it means that the function output can be made arbitrarily close to $L$ by requiring $x$ to be sufficiently close to $c$.

At least on the AP Exam, visual estimations of limits will be relatively straightforward. Using a table is also straightforward, but tedious. 

haha gl xd

The formal definition of limit is as follows: $ \forall \epsilon > 0, \exists \delta > 0 : |x - c| < \delta \Rightarrow |f(x) - L| < \epsilon. $ This follows the intuitive definition almost exactly. 

For any $\epsilon$ (output error bound), we want $|f(x) - L| < \epsilon$. In other words, we want the difference between the limit value and the function output to be at most $\epsilon$.

This can be achieved by requiring $|x - c| < \delta$ for some $\delta$ (input error bound) that we can find. In other words, we can require the difference between $x$ and the limit point to be at most $\delta$. Then, the *output bound* can be achieved with this requirement of an *input bound*. 


## 1.2: Limit evaluation

This section departs from *estimating* the limit to actually *evaluating* the limit. Various algebraic tools are used to transform our functions into something that we can easily find the limit of. 

Direct substitution can be used in a fair amount of cases, but these are cases when the function is *continuous* (oo were gona learn in the next secitno omgg): 
- constant functions $f(x) = c$
- plain line $f(x) = x$
- plain monomials $f(x) = x^n$
- basic radicals $f(x) = \sqrt[n]{x}$ (on its domain)
- the 6 basic trigonometric functions (on its domain)

Operations of functions with defined limits also have a limit: 
- linear combination $af(x)+bg(x)$
- product of functions $f(x)g(x)$
- quotient of functions $\frac{f(x)}{g(x)}$ (as long as the limit of $g(x) \neq 0$ at the limit point in question)
- power of a function $[f(x)]^n$

Composite functions $f(g(x))$ also have limits, under certain conditions. 

For quotients of functions, if direct substitution results in $\frac{0}{0}$, then we call this an indeterminate form, since we are unable to determine the limit. The limit could be any real number, or not exist at all. Thus, we must use other methods to evaluate the limit. This section covers the algebraic ways to approach this issue, including factorization and rationalization. 

## 1.3: Squeeze theorem

The ~~skinny legend~~ Squeeze Theorem provides a very powerful, albeit incredibly conditional, tool to calculate limits. The Squeeze theorem can be looked at as the strictest version of function bounding, and we look at some ways that bounding/squeeze presents itself in the context of functions, particularly when there is a trigonometric part of the function. 

One of the main uses of the Squeeze theorem is that it gives way to the limit of $\frac{\sin{x}}{x}$, which unlocks a bunch of other ways to calculate the limits of other weird trigonometric functions. 

## 1.4: Continuity and discontinuity

Limits pave the way to continuity. For some point, when the limit exists at that point and is equal to the function's value, then the function is continuous. These conditions give rise to the multiple ways that a function can be discontinuous, all of which are discussed in this section. 

Continuity over an interval is met when the function is continuous at every single point within the interval, and if endpoints are included, then the corresponding one-sided limit also equals the function value at the endpoint.

Discontinuities have a few major types: asymptotes, removable discontinuities, and jump discontinuities. Removable continuities, as the name suggests, can be removed by redefining the function at that specific discontinuous point. 

## 1.5: Intermediate value theorem

The Intermediate Value Theorem is one of the major theorems that function continuity guarantees. Various simple applications are discussed, such as how the Borsak-Ulam theorem guarantees a pair of antipodal points on Earth with the same temperature and air pressure. 

## 1.6: Asymptotes

Veritcal asymptotes were briefly discussed during 1.4 when discontinuites were discussed. This section looks more closely at asymptotes as a whole, including vertical asymptotes, horizontal asymptotes, and other function behaviors as we let $x \rightarrow \pm \infty$. Particularly, the behavior of a quotient of polynomials can be found easily by looking at the leading term exponent and coefficient values. 
