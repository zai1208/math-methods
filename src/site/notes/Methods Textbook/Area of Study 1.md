---
{"dg-publish":true,"dg-path":"Area of Study 1.md","permalink":"/area-of-study-1/"}
---

From the study design:

> In this area of study students cover transformations of the plane and the behaviour of some elementary functions of a single real variable, including key features of their graphs such as axis intercepts, stationary points, points of inflection, domain (including maximal, implied or natural domain), co-domain and range, asymptotic behaviour and symmetry. The behaviour of functions and their graphs is to be explored in a variety of modelling contexts and theoretical investigations.

I will take you through this topic in the order of set theory, relations, functions, and graphs.

Don't worry, this will be fun.

# Set Theory

Now this isn't in the study design, but you're expected to know it anyways.

Set theory is basically any type of math to do with sets that are literally just groups of items related in some way, shape, or form.

In methods we only deal with sets of numbers.

This is a diagram of all numbers:

![Venn_Diagram_of_Numbers_Expanded.svg.png](/img/user/Methods%20Textbook/Venn_Diagram_of_Numbers_Expanded.svg.png)
Now don't worry if you don't understand what all these letters mean, we'll go through them in a second.

$\mathbb{N}$ is the set of all natural numbers. What is that? Literally just all positive integers (whole number). The numbers that you thought were the only existent ones when you were younger.

$\mathbb{Z}$ is an **extension** of $\mathbb{N}$ to also include $0$ and negative integers as well

$\mathbb{Q}$ is an extension to $\mathbb{Z}$ to also include any number which can be expressed a fraction, aka rational numbers.

$\mathbb{R}$ is the set that encompasses $\mathbb{Q}$ and $\mathbb{I}$ which is the set of irrational numbers, basically numbers like $\sqrt{2}$, $\pi$, etc.

Complex and imaginary numbers aren't talked about in methods so we son't go over them.

Now all of these can be expressed on the number line, but when we want to talk about subsets (part of a set) we use something called set notation.

Set notation is methods is generally used to refer to a subset of the number line ($\mathbb{R}$) unless otherwise specified.

The notation is very simple and is used as follows:

- $(a,b)$ with parentheses represents a subset of $\mathbb{R}$ containing all numbers from $a$ to $b$ but **not** including $a$ and $b$
- $[a,b]$ with square brackets represents a subset of $\mathbb{R}$ containing all numbers from $a$ to $b$ **including** $a$ and $b$
- $\{a, b, c, \dots\}$ with curly braces represents a set containing only the values specified in it (aka a list)

(Yes the first two notations can be mixed to produce $[a,b)$ and $(a,b]$)

To combine sets or to exclude from sets we use the following notation:

- $a \cup b$ where $a$ and $b$ are sets (using either of the 3 notations mentioned above). This gives us the set at the **union** of $a$ and $b$ (i.e. **all** the values in $a$ and $b$ combined but excluding the duplicates)
- $a \cap b$ where $a$ and $b$ are sets (using either of the 3 notations mentioned above). This gives us the set at the **intersection** of $a$ and $b$ (i.e. what values are included in **both** $a$ and $b$)
- $a\setminus b$ means what values are in a but are **not** in b (This is most commonly seen to exclude a number/set of numbers from $\mathbb{R}$, for example $\mathbb{R} \setminus \{2\}$ which means all real numbers except for 2)

Now you might be wondering if we're getting anywhere close to functions with this. We absolutely are.

# Relations

This is the cartesian plane

<script src="https://www.desmos.com/api/v1.9/calculator.js?apiKey=dcb31709b452b1cf9dc26972add0fda6"></script>

<div id="cartesian plane" style="width: 600px; height: 600px;"></div>


<script>
  var elt = document.getElementById('cartesian plane');
  var calculator = Desmos.GraphingCalculator(elt, {lockViewport: true, expressionsCollapsed : true, expressions: false, settingsMenu : false});
</script>



