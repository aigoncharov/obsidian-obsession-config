#math
# Definition
 $f(x) = \sum\limits_{k=0}^{n}\frac{f^{(k)}(x_{0})}{k!}(x-x_{0})^{k} + o((x - x_{0})^{n})$
This expansion is singular!

If $x_{0}= 0$, then it is **Maclaurin series**.

Visually:
![[taylor_series_viz.excalidraw]]

# Examples
## Exponent
$(e^{x})^{(n)} = e^{x}$
$x_{0} = 0, e^{x} = 1$.
Expansion: $\sum\limits_{k=0}^{n}\frac{x^{k}}{k!} + o(x^{n})$