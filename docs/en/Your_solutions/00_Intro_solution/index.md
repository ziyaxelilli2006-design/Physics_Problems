Let's elevate the presentation with a highly structured, "Master Class" version of these solutions. I've broken each problem down into its **Core Concept**, **Step-by-Step Execution**, and **Final Result**, including visual cues to help you "see" the math.

---

## 1. Vector Algebra

**The Setup:** We have $\vec{a} = [2, 1, -3]$ and $\vec{b} = [4, -2, 1]$.

### a) Magnitudes (Length)

Think of the magnitude as the "straight-line distance" from the start of the vector to its tip.

* **For $|\vec{a}|$:** $\sqrt{2^2 + 1^2 + (-3)^2} = \sqrt{14} \approx \mathbf{3.74}$
* **For $|\vec{b}|$:** $\sqrt{4^2 + (-2)^2 + 1^2} = \sqrt{21} \approx \mathbf{4.58}$

### b) Dot Product ($\vec{a} \cdot \vec{b}$)

The dot product measures how much one vector "overlaps" with another. It results in a single number (scalar).

* **Calculation:** Multiply corresponding parts and sum them: $(2 \times 4) + (1 \times -2) + (-3 \times 1) = 8 - 2 - 3 = \mathbf{3}$

### c) Cross Product ($\vec{a} \times \vec{b}$)

This creates a new vector that is perfectly perpendicular to both original vectors.

* **The Matrix:**

$$\begin{vmatrix} \mathbf{i} & \mathbf{j} & \mathbf{k} \\ 2 & 1 & -3 \\ 4 & -2 & 1 \end{vmatrix}$$


* **$x$-component:** $(1 \cdot 1) - (-3 \cdot -2) = 1 - 6 = -5$
* **$y$-component:** $-[(2 \cdot 1) - (-3 \cdot 4)] = -(2 + 12) = -14$
* **$z$-component:** $(2 \cdot -2) - (1 \cdot 4) = -4 - 4 = -8$
* **Result:** $\mathbf{[-5, -14, -8]}$

### d) Angle between vectors

* **Formula:** $\cos(\theta) = \frac{\vec{a} \cdot \vec{b}}{|\vec{a}| |\vec{b}|}$
* **Calculation:** $\frac{3}{\sqrt{14} \cdot \sqrt{21}} \approx 0.175$
* **Angle:** $\theta = \arccos(0.175) \approx \mathbf{79.9^\circ}$

---

## 2. Systems of Equations

**Equations:** (1) $2x + 3y = 12$ and (2) $x - y = 1$

1. **Isolate:** From equation (2), isolate $x$: $x = y + 1$.
2. **Substitute:** Plug this into equation (1): $2(y + 1) + 3y = 12$.
3. **Expand and Combine:** $2y + 2 + 3y = 12 \rightarrow 5y = 10$.
4. **Solve:** $y = 2$.
5. **Finish:** If $y = 2$, then $x = 2 + 1 = 3$.
**Solution Point:** $(3, 2)$

---

## 3. Proportionality (Universal Gravity)

**The Formula:** $F = G \frac{m_1 m_2}{r^2}$

* **The Change:** Double the distance ($2r$) and halve both masses ($\frac{1}{2}m$).
* **The Math:**

$$F_{new} = G \frac{(\frac{1}{2} m_1)(\frac{1}{2} m_2)}{(2r)^2} = G \frac{\frac{1}{4} m_1 m_2}{4r^2} = \frac{1}{16} \cdot F_{original}$$


* **Result:** The force is reduced by a factor of **16**.

---

## 4. Rearranging Formulas (Pendulum)

**Starting Formula:** $T = 2\pi \sqrt{\frac{L}{g}}$

1. **Remove the $2\pi$:** $\frac{T}{2\pi} = \sqrt{\frac{L}{g}}$
2. **Remove the Root:** Square both sides: $\frac{T^2}{4\pi^2} = \frac{L}{g}$
3. **Isolate $g$:** $g = \frac{4\pi^2 L}{T^2}$

---

## 5. Trigonometry (Vector Components)

**Vector:** Magnitude $15$ at $60^\circ$ to the horizontal.

* **Horizontal ($A_x$):** $15 \cdot \cos(60^\circ) = 15 \cdot 0.5 = \mathbf{7.5}$
* **Vertical ($A_y$):** $15 \cdot \sin(60^\circ) = 15 \cdot \frac{\sqrt{3}}{2} \approx \mathbf{12.99}$

---

## 6. Function Analysis

**Function:** $f(x) = 3x^2 - 12x + 7$

1. **Find the Slope ($f'$):** $f'(x) = 6x - 12$.
2. **Set to Zero:** $6x - 12 = 0 \rightarrow x = 2$.
3. **Identify Point Type:** The second derivative is $f''(x) = 6$ (Positive = Smile = Minimum).
4. **Find the Coordinate:** $f(2) = 3(4) - 24 + 7 = -5$.
**Local Minimum:** $(2, -5)$

---

## 7. Logic & Series (The Fly and the Bike)

**The Scenario:** Bicycle moves at 1 m/s across 10m. Fly flies at 2 m/s back and forth.

1. **The Trick:** Ignore the back-and-forth turns! Simply ask: *How long is the fly flying?*
2. **Time:** The bike reaches the wall in $10\text{ m} \div 1\text{ m/s} = 10\text{ seconds}$.
3. **Fly Distance:** The fly flies for 10 seconds at 2 m/s.
**Distance:** $2\text{ m/s} \times 10\text{ s} = \mathbf{20\text{ meters}}$.

---

## 8. Definite Integrals

**The Problem:** Area under $\sin(x)$ from $0$ to $\pi$.

1. **The Integral:** $\int_{0}^{\pi} \sin(x) dx = [-\cos(x)]_{0}^{\pi}$
2. **Evaluation:** $(-\cos(\pi)) - (-\cos(0)) = (-(-1)) - (-1) = 1 + 1 = \mathbf{2}$.

---

## 9. Optimization

**Area of rectangle** under $y = 3 - x^2$ in the first quadrant.

1. **Area Function:** $A = x \cdot y = x(3 - x^2) = 3x - x^3$.
2. **Maximize:** Take the derivative $A'(x) = 3 - 3x^2$ and set to zero.
3. **Solve:** $3x^2 = 3 \rightarrow x = 1$.
4. **Find height:** $y = 3 - (1)^2 = 2$.
**Optimal Dimensions:** $1 \times 2$

---

## 10. Infinite Series

**The Ant's Final Position:**

1. **Horizontal ($x$):** $1 - \frac{1}{3} + \frac{1}{5} - \dots$ This is the Leibniz formula for **$\frac{\pi}{4}$**.
2. **Vertical ($y$):** $\frac{1}{2} - \frac{1}{4} + \frac{1}{6} - \dots$ This is half of the alternating harmonic series ($\ln(2)$), giving **$\frac{\ln(2)}{2}$**.
**Coordinate:** $(\approx 0.785, \approx 0.347)$

Would you like me to create a visual cheatsheet with these formulas that you can save for future reference?