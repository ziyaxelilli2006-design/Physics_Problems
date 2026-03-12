
---

## 6. Function Analysis: Finding Extrema

### The Theory: Derivatives as Slope

To find a "local maximum" (a peak) or a "local minimum" (a valley), we look for where the function is momentarily **flat**.

1. **The First Derivative ($f'(x)$):** This tells us the slope of the function. At the very top of a hill or bottom of a valley, the slope is exactly **zero**.
2. **The Second Derivative ($f''(x)$):** This tells us the "concavity" (the curvature).
* If $f''(x)$ is **positive**, the graph is shaped like a cup (U), meaning the point is a **minimum**.
* If $f''(x)$ is **negative**, the graph is shaped like a frown ($\cap$), meaning the point is a **maximum**.



---

### Step-by-Step Calculation

**Given Function:** $f(x) = 3x^2 - 12x + 7$

#### Step 1: Find the First Derivative

Using the power rule ($\frac{d}{dx} x^n = nx^{n-1}$):

* The derivative of $3x^2$ is $6x$.
* The derivative of $-12x$ is $-12$.
* The derivative of a constant ($7$) is $0$.

$$f'(x) = 6x - 12$$

#### Step 2: Find the Critical Point

Set the derivative to zero to find where the slope is flat:


$$6x - 12 = 0$$

$$6x = 12$$

$$\mathbf{x = 2}$$


This is the horizontal location of our "peak" or "valley."

#### Step 3: Determine if it's a Max or Min

Take the second derivative ($f''(x)$) by differentiating $6x - 12$:


$$f''(x) = 6$$


Since $6$ is a **positive** number, the function is "concave up" (it opens upwards). This confirms that our point at $x=2$ is a **local minimum**.

#### Step 4: Find the y-coordinate

Plug $x=2$ back into the original function to find the exact location of the valley:


$$f(2) = 3(2)^2 - 12(2) + 7$$

$$f(2) = 3(4) - 24 + 7$$

$$f(2) = 12 - 24 + 7 = \mathbf{-5}$$

---

### Final Result

The function has a **local minimum at the point $(2, -5)$**. There are no local maxima for this specific function as it is a parabola that opens infinitely upwards.

**Mathematical Intuition:** Think of this function like a physical valley. If you dropped a ball into this curve, it would eventually roll down and settle at the lowest possible point: $x=2$, which sits at a height of $-5$.

