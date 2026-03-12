
---

## 10. Infinite Series: The Ant’s Final Position

### The Theory: Vector Summation of Series

As the ant moves, its position $(x, y)$ is the sum of every step it has taken. Because the directions alternate (East then West, North then South) and the distances decrease ($1, 1/2, 1/3 \dots$), we are dealing with **Alternating Harmonic Series**.

---

### Step-by-Step Calculation

#### Step 1: Analyze the Horizontal Position ($x$)

The ant moves East (+), then West (-), then East (+), following the odd denominators:


$$x = 1 - \frac{1}{3} + \frac{1}{5} - \frac{1}{7} + \frac{1}{9} - \dots$$


**The Theory:** This is the famous **Leibniz formula for $\pi$**. It is known that this specific infinite series converges exactly to:


$$x = \frac{\pi}{4} \approx \mathbf{0.785\text{ m}}$$

#### Step 2: Analyze the Vertical Position ($y$)

The ant moves North (+), then South (-), then North (+), following the even denominators:


$$y = \frac{1}{2} - \frac{1}{4} + \frac{1}{6} - \frac{1}{8} + \frac{1}{10} - \dots$$


**The Theory:** We can factor out a $1/2$ from this series:


$$y = \frac{1}{2} \left( 1 - \frac{1}{2} + \frac{1}{3} - \frac{1}{4} + \dots \right)$$


The part inside the parentheses is the alternating harmonic series, which is the Taylor expansion for $\ln(1+x)$ when $x=1$. Therefore, it equals $\ln(2)$.


$$y = \frac{1}{2} \ln(2) = \frac{\ln(2)}{2} \approx \mathbf{0.347\text{ m}}$$

---

### Final Result

The ant’s final destination (the point it will infinitely approach but never quite pass) is:


$$\text{Position} = \left( \frac{\pi}{4}, \frac{\ln(2)}{2} \right) \approx \mathbf{(0.785, 0.347)}$$

**Mathematical Intuition:** Even though the ant keeps moving forever, the steps get so small so quickly that it gets "trapped" at a specific coordinate. It’s a paradox of infinity: the ant travels an infinite distance in terms of steps ($1 + 1/2 + 1/3 \dots$ diverges), yet it ends up at a very specific, finite point on the map!

---

