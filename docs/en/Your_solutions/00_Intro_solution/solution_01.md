
## 1. Vector Algebra Masterclass

We are working with two vectors in 3D space:


$$\vec{a} = [2, 1, -3] \quad \text{and} \quad \vec{b} = [4, -2, 1]$$

### a) Magnitude: "How long is the arrow?"

The magnitude of a vector is its length. In 3D space, we use a three-dimensional version of the Pythagorean theorem. If a vector is $[x, y, z]$, its magnitude $|\vec{v}|$ is:


$$|\vec{v}| = \sqrt{x^2 + y^2 + z^2}$$

* **For $\vec{a}$:** 
$$|\vec{a}| = \sqrt{2^2 + 1^2 + (-3)^2} = \sqrt{4 + 1 + 9} = \mathbf{\sqrt{14}} \approx 3.74$$


* **For $\vec{b}$:** 
$$|\vec{b}| = \sqrt{4^2 + (-2)^2 + 1^2} = \sqrt{16 + 4 + 1} = \mathbf{\sqrt{21}} \approx 4.58$$



---

### b) Dot Product: "How much do they align?"

The dot product ($\vec{a} \cdot \vec{b}$) is a **scalar** (a single number). It tells you how much of one vector "goes in the direction" of the other. We calculate it by multiplying the corresponding components and adding them up:

$$\vec{a} \cdot \vec{b} = (a_x \cdot b_x) + (a_y \cdot b_y) + (a_z \cdot b_z)$$

* **Calculation:**

$$\vec{a} \cdot \vec{b} = (2 \cdot 4) + (1 \cdot -2) + (-3 \cdot 1)$$


$$\vec{a} \cdot \vec{b} = 8 - 2 - 3 = \mathbf{3}$$


* **Insight:** Since the result is positive, the vectors are generally pointing in the same direction (the angle between them is less than $90^\circ$).

---

### c) Cross Product: "Building a new direction"

Unlike the dot product, the cross product ($\vec{a} \times \vec{b}$) results in a **new vector**. This new vector is special because it is **perpendicular (orthogonal)** to both $\vec{a}$ and $\vec{b}$.

We calculate it using the determinant of a matrix:


$$\vec{a} \times \vec{b} = \begin{vmatrix} \mathbf{i} & \mathbf{j} & \mathbf{k} \\ 2 & 1 & -3 \\ 4 & -2 & 1 \end{vmatrix}$$

1. **For $\mathbf{i}$:** $(1 \cdot 1) - (-3 \cdot -2) = 1 - 6 = -5$
2. **For $\mathbf{j}$:** $-[(2 \cdot 1) - (-3 \cdot 4)] = -(2 + 12) = -14$
3. **For $\mathbf{k}$:** $(2 \cdot -2) - (1 \cdot 4) = -4 - 4 = -8$

* **Result:** $\vec{a} \times \vec{b} = \mathbf{[-5, -14, -8]}$

---

### d) Angle between vectors: "The spatial relationship"

To find the angle $\theta$, we use the geometric definition of the dot product:


$$\vec{a} \cdot \vec{b} = |\vec{a}| |\vec{b}| \cos(\theta)$$

1. **Rearrange for $\cos(\theta)$:** 
$$\cos(\theta) = \frac{\vec{a} \cdot \vec{b}}{|\vec{a}| |\vec{b}|}$$


2. **Plug in our previous answers:**

$$\cos(\theta) = \frac{3}{\sqrt{14} \cdot \sqrt{21}} = \frac{3}{\sqrt{294}} \approx \frac{3}{17.15} \approx 0.175$$


3. **Find the inverse cosine:**

$$\theta = \arccos(0.175) \approx \mathbf{79.92^\circ}$$



---

**Summary Table**

| Property | Formula | Result |
| --- | --- | --- |
| **Magnitude $ | \vec{a} | $** |
| **Magnitude $ | \vec{b} | $** |
| **Dot Product** | $a_x b_x + a_y b_y + a_z b_z$ | $3$ |
| **Cross Product** | Determinant | $[-5, -14, -8]$ |
| **Angle $\theta$** | $\arccos\left(\frac{\vec{a} \cdot \vec{b}}{ | \vec{a} |

