---
{"dg-publish":true,"dg-path":"Area of Study 1.md","permalink":"/area-of-study-1/"}
---

# Area of Study 1

From the study design:

> In this area of study students cover transformations of the plane and the behaviour of some elementary functions of a single real variable, including key features of their graphs such as axis intercepts, stationary points, points of inflection, domain (including maximal, implied or natural domain), co-domain and range, asymptotic behaviour and symmetry. The behaviour of functions and their graphs is to be explored in a variety of modelling contexts and theoretical investigations.

# Polynomials

The study design asks for you to be able to graph polynomials **and** describe their key features.

Now the study design doesn't specify any specific degree of polynomial to focus on, but it is very simple to find the general form of any degree polynomial.

A polynomial of degree $n$ is defined by
$$ P(x)=a_{n}x^n + a_{n-1}x^{n-1} +\dots +a_{1}x + a_{0}$$
where $a_{n}, a_{n-1}, \dots$ are coefficients of $x$ that are **not** the same number and can be replaced by different letters of the alphabet. 

The degree of a polynomial is the power of $x$ that is the largest power in the entire function, which in our case happens to be $n$

For example:
A polynomial of degree 2 (quadratic) would be defined by
$$
P(x)=a_{2}x^2+a_{1}x+a_{0}
$$
but $a_{2},a_{1}$ and $a_{0}$ can be replaced by $a,b$ and $c$. This becomes:
$$
P(x)=ax^2+bx+c
$$
We can extend this definition to a polynomial of any degree where for a polynomial of degree $n$ there are $n+1$ coefficients.

Now some polynomials can also be rewritten in turning point form which if you remember from Units 1&2 can be found by completing the square for a quadratic polynomial. Turning point form is: $$y=a(x-h)^n+k$$where $a,h$ and $k$ are transformations (more on them later, but you should've already seen them in Units 1&2) and $n$ is the degree of the polynomial.

## Graphing Polynomials

Even polynomials (i.e. with an even degree which means that $n$ is even) generally follow the same shape which consists of the function decreasing in value for negative values of $x$ hitting a "turning point" and then increasing in value for positive values of $x$.

```functionplot
---
title: Graphs of even polynomial functions
xLabel: x
yLabel: y
bounds: [-10, 10, -2, 18]
disbaleZoom: 1
grid: true
---
f(x)=x^2
g(x)=x^4
h(x)=x^6
```


Odd polynomials (i.e. an odd degree or $n$ is an odd number) have a different general pattern where the function is always increasing for all values of $x$ but has a "stationary point" at $x=0$. Again, transformations also apply here but will be discussed in transformations. and generally look like this:

```functionplot
---
title: Graphs of odd polynomial functions
xLabel: x
yLabel: y
bounds: [-10, 10, -10, 10]
disbaleZoom: 1
grid: true
legends: true
---
f(x)=x^3
x^5
x^7
```

You may have already noticed a pattern in both even and odd polynomial graphs which we will get to later on. There is one more aspect of graphing which we will discuss when we get to transformations.

# Further functions

There are 4 more types of functions VCAA wants you to be able to graph and identify key points for:
- Power functions: $y=x^n$,$n \in \mathbb{Q}$
- Exponential functions: $y=a^x$,$a \in \mathbb{R}$ (in particular $y=e^x$)
- Logarithmic functions: $y=\log_{e}x$ and $y=\log_{10}x$
- And Circular functions: $y=\sin(x)$, $y=\cos(x)$, $y=\tan(x)$

You would've already learnt circular, logarithmic, and exponential functions in Units 1 & 2 so we will just briefly show their graphs here

<center> <h3> Graphs of <span class="math display">a^x</span> </h3></center>

```functionplot
{
  "constants": {},
  "legends": true,
  "xAxis": {
    "domain": {
      "min": -10,
      "max": 10
    },
    "label": "x"
  },
  "yAxis": {
    "domain": {
      "min": -10,
      "max": 10
    },
    "label": "y"
  },
  "grid": true,
  "data": [
    {
      "id": "gl5ysyt",
      "scope": {},
      "fnType": "linear",
      "closed": false,
      "offset": {},
      "vector": {},
      "range": {},
      "skipTip": false,
      "graphType": "polyline",
      "points": [
        [
          0,
          0
        ]
      ],
      "derivative": {
        "fn": "",
        "updateOnMouseMove": true
      },
      "color": "#ff0000",
      "name": "2^x",
      "fn": "2^x"
    },
    {
      "id": "2j4xscu",
      "scope": {},
      "fnType": "linear",
      "closed": false,
      "offset": {},
      "vector": {},
      "range": {},
      "skipTip": false,
      "graphType": "polyline",
      "points": [
        [
          0,
          0
        ]
      ],
      "derivative": {
        "fn": "",
        "updateOnMouseMove": true
      },
      "color": "#00ff00",
      "name": "3^x",
      "fn": "3^x"
    },
    {
      "id": "xhgz5ik",
      "scope": {},
      "fnType": "linear",
      "closed": false,
      "offset": {},
      "vector": {},
      "range": {},
      "skipTip": false,
      "graphType": "polyline",
      "points": [
        [
          0,
          0
        ]
      ],
      "derivative": {
        "fn": "",
        "updateOnMouseMove": true
      },
      "color": "#ffff00",
      "name": "4^x",
      "fn": "4^x"
    },
    {
      "id": "bh2qwvw",
      "scope": {},
      "fnType": "linear",
      "closed": false,
      "offset": {},
      "vector": {},
      "range": {},
      "skipTip": false,
      "graphType": "polyline",
      "points": [
        [
          0,
          0
        ]
      ],
      "derivative": {
        "fn": "",
        "updateOnMouseMove": true
      },
      "color": "#0a64ff",
      "fn": "5^x",
      "name": "5^x"
    }
  ],
  "tip": {
    "renderer": "",
    "yLine": true,
    "xLine": true
  },
  "title": "",
  "target": null
}
```




```functionplot
---
title: Graph of sin(x)
xLabel: x
yLabel: y
bounds: [-10, 10, -2, 2]
disbaleZoom: 1
grid: true
---
f(x)=sin(x)
```

```functionplot
---
title: Graph of cos(x)
xLabel: x
yLabel: y
bounds: [-10, 10, -2, 2]
disbaleZoom: 1
grid: true
---
f(x)=cos(x)
```

```functionplot
---
title: Graph of tan(x)
xLabel: x
yLabel: y
bounds: [-10, 10, -2, 2]
disbaleZoom: 1
grid: true
---
f(x)=tan(x)
```
