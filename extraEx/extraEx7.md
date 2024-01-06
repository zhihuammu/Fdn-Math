(chap07-extraEx)=
# Challenging Exercise 7


%Q1
:::{exercise}
  $y=f(x)$ is an even function and it is symmetric about the $y-$axis
($x=0$). Then the function $y=f(x-1)$ symmetric about:

1.  $x=0$ 
1.  $x=1$ 
1.  $x=-1$ 
1.  $x=2$

:::

:::{admonition} solution
:class: solution

Supposing $f(x)=x^2$, it is an even function and symmetric about $x=0$. We could obtain $f(x-1)=(x-1)^2$, it is symmetric about $x=1$ as shown in the following figure.

```{tikz} Sequence and interpolation.
:xscale: 60
\tkzInit[xmin=-5,ymin=-1,xmax=5,ymax=9]
\tkzGrid[very thin]
\tkzAxeXY[noticks]
\draw[thick,color=blue,domain=3:-3]  plot ({\x},{\x*\x}) node[left] {$y = x^2$};
\draw[thick,color=red,domain=-2:4 ]  plot ({\x},{(\x-1)*(\x-1)}) node[right] {$y = (x-1)^2$};;       
```
:::
 