

## 8. Definite Integrals: Area Under a Curve

### The Theory: The Fundamental Theorem of Calculus

To find the area between a curve $f(x)$ and the $x$-axis, we use a "definite integral." Think of this as slicing the area into an infinite number of incredibly thin rectangles and adding their areas together.

The area $A$ is given by:


$$A = \int_{a}^{b} f(x) \, dx$$

Where:

* $\int$ is the integral symbol (representing a sum).
* $a$ and $b$ are the boundaries ($0$ and $\pi$).
* $f(x)$ is the height of the curve ($\sin x$).
* $dx$ is the width of our infinitely thin slices.

---

### Step-by-Step Calculation

**Given Function:** $f(x) = \sin(x)$ from $x = 0$ to $x = \pi$.

#### Step 1: Find the Anti-derivative

We need to find a function which, when differentiated, gives us $\sin(x)$.

* We know the derivative of $\cos(x)$ is $-\sin(x)$.
* Therefore, the anti-derivative of $\sin(x)$ is **$-\cos(x)$**.

#### Step 2: Set up the Evaluation

We write this using the evaluation bracket notation:


$$\int_{0}^{\pi} \sin(x) \, dx = [-\cos(x)]_{0}^{\pi}$$

#### Step 3: Apply the Boundaries (Top minus Bottom)

According to the Fundamental Theorem of Calculus, we plug in the top number ($\pi$) first, then subtract the result of plugging in the bottom number ($0$):


$$\text{Area} = (-\cos(\pi)) - (-\cos(0))$$

#### Step 4: Calculate the Values

Using the unit circle:

* $\cos(\pi) = -1$
* $\cos(0) = 1$

Now, be very careful with the negative signs:


$$\text{Area} = (-(-1)) - (-1)$$

$$\text{Area} = (1) - (-1)$$

$$\text{Area} = 1 + 1 = \mathbf{2}$$

---

### Final Result

The area under the sine curve from $0$ to $\pi$ is exactly **$2$ square units**.

**Mathematical Insight:** It is a beautiful result of calculus that such a complex, rounded shape results in a perfectly clean integer. Even though the curve involves $\pi$ (an irrational number) in its boundaries, the total "stuff" inside that specific hump of the wave adds up to exactly $2$.

