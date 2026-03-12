
## 9. Optimization: Rectangle Under a Curve

### The Theory: Objective Functions

When we optimize, we are looking for a peak on a graph. We follow three main steps:

1. **Define the Area:** Create a formula for the area ($A$) in terms of just one variable ($x$).
2. **Find the Derivative ($A'$):** This tells us the rate of change of the area.
3. **Find the Critical Point:** Set that derivative to zero. Where the change is zero, the area is at its maximum.

---

### Step-by-Step Calculation

**The Setup:**

* The curve is $y = 3 - x^2$.
* The rectangle is in the first quadrant (where $x$ and $y$ are positive).
* The corners of the rectangle are at $(0,0)$, $(x,0)$, $(x, y)$, and $(0, y)$.

#### Step 1: Write the Area Equation

The area ($A$) of a rectangle is $\text{width} \times \text{height}$.

* Width = $x$
* Height = $y$ (which we know is $3 - x^2$)

$$A = x \cdot (3 - x^2)$$


$$A(x) = 3x - x^3$$



#### Step 2: Differentiate to find the "Slope" of the Area

To find the maximum area, we find $A'(x)$ using the power rule:


$$A'(x) = 3 - 3x^2$$

#### Step 3: Solve for $x$ (Set $A'$ to 0)

$$0 = 3 - 3x^2$$

$$3x^2 = 3$$

$$x^2 = 1$$

$$\mathbf{x = 1}$$


*(We ignore $x = -1$ because the problem specifies the first quadrant).*

#### Step 4: Find the corresponding height ($y$)

Plug $x = 1$ back into our curve equation to find the height:


$$y = 3 - (1)^2$$

$$\mathbf{y = 2}$$

---

### Final Result

The dimensions of the rectangle with the maximum area are a **width of $1$** and a **height of $2$**.

**Geometric Intuition:** If you make the rectangle too wide (like $x=1.5$), it becomes very short and loses area. If you make it too tall ($x=0.5$), it becomes very skinny and loses area. The "Goldilocks" point where the area is perfectly maximized happens exactly when the width is $1$.

