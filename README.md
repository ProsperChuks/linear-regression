# linear-regression

a simple linear regression model without any machine learning libraries

using:

y = (slope)x-var + y-intercept

slope = (m(x) * m(y)) - m(x * y) / m(x)^2 - m(x^2)

y-intercept = m(y) - slope(m(x))

---
header-includes:
    - \usepackage[most]{tcolorbox}
    - \definecolor{light-yellow}{rgb}{1, 0.95, 0.7}
    - \newtcolorbox{myquote}{colback=light-yellow,grow to right by=-10mm,grow to left by=-10mm, boxrule=0pt,boxsep=0pt,breakable}
    - \newcommand{\Note}[1]{\begin{myquote} \textbf{Note:} \emph{#1} \end{myquote}}
---

**_Note:_** be sure to follow the PEMDAS order of operations
