Welcome to **Section 1: Mechanics I**. We’re moving from pure math into the physical world—where things have mass, direction, and a tendency to hit the ground.

Let's break these down step-by-step with a focus on how vectors and calculus describe reality.

---

## 1. Projectile Motion

**Given:** $v_0 = 100 \text{ m/s}$, $\theta = 37^\circ$ ($\sin 37^\circ \approx 0.6$, $\cos 37^\circ \approx 0.8$).

* **Differential Equations:**
In a vacuum, gravity only acts vertically ($y$).
* **Horizontal:** $\frac{d^2x}{dt^2} = 0$ (No acceleration).
* **Vertical:** $\frac{d^2y}{dt^2} = -g$ (Constant acceleration downward).


* **Initial Components:**
* $v_{0x} = 100 \cos(37^\circ) = 80 \text{ m/s}$
* $v_{0y} = 100 \sin(37^\circ) = 60 \text{ m/s}$


* **Time of Flight ($T$):**
The projectile is in the air until $y = 0$. Using $y = v_{0y}t - \frac{1}{2}gt^2$:
$0 = 60T - 5T^2 \implies 5T(12 - T) = 0$.
**$T = 12 \text{ seconds}$.**
* **Maximum Height ($H$):**
Occurs when $v_y = 0$ (at $t = 6\text{s}$).
$H = v_{0y}(6) - \frac{1}{2}g(6)^2 = 60(6) - 5(36) = 360 - 180 = \mathbf{180 \text{ meters}}$.
* **Range ($R$):**
The horizontal distance covered in $T=12\text{s}$.
$R = v_{0x} \times T = 80 \times 12 = \mathbf{960 \text{ meters}}$.

---

## 2. Range Optimization

**Goal:** Show $R$ is max at $45^\circ$.
The range formula is $R(\theta) = \frac{v_0^2 \sin(2\theta)}{g}$.
To find the maximum, we take the derivative with respect to $\theta$ and set it to zero:


$$\frac{dR}{d\theta} = \frac{v_0^2}{g} \cdot \cos(2\theta) \cdot 2 = 0$$


For this to be zero, $\cos(2\theta) = 0$. The first positive angle where cosine is zero is $90^\circ$.
$2\theta = 90^\circ \implies \mathbf{\theta = 45^\circ}$.

---

## 3. Path Intersection (Alice & Bob)

* **Alice:** $x_A = 2+t, y_A = 8-3t$
* **Bob:** $x_B = 2t-1, y_B = 2t+2$

**Do they collide?** (Same place, same time $t$):

1. Set $x_A = x_B$: $2+t = 2t-1 \implies \mathbf{t = 3}$.
2. Check $y$ at $t=3$:
* Alice: $y_A = 8 - 3(3) = -1$.
* Bob: $y_B = 2(3) + 2 = 8$.
Since $-1 \neq 8$, they **do not collide**.



**Do the paths intersect?** (Same place, different times $t_1, t_2$):
Solve $2+t_1 = 2t_2-1$ and $8-3t_1 = 2t_2+2$.
From the first: $t_1 = 2t_2 - 3$.
Substitute into second: $8 - 3(2t_2 - 3) = 2t_2 + 2 \implies 8 - 6t_2 + 9 = 2t_2 + 2 \implies 15 = 8t_2 \implies t_2 = 1.875$.
Then $t_1 = 2(1.875) - 3 = 0.75$.
**The paths intersect** at the coordinates $(2.75, 5.75)$.

---

## 4. Vector Calculus

**Position:** $\vec{r}(t) = (3t^2)\hat{i} + (5t - 8t^2)\hat{j}$

* **Velocity ($\vec{v} = \frac{d\vec{r}}{dt}$):** Differentiate each component:
$\mathbf{\vec{v}(t) = (6t)\hat{i} + (5 - 16t)\hat{j}}$
* **Acceleration ($\vec{a} = \frac{d\vec{v}}{dt}$):**
Differentiate velocity:
$\mathbf{\vec{a}(t) = (6)\hat{i} + (-16)\hat{j}}$

---

## 5. Relative Velocity

* $v_{river} = 2 \text{ m/s (East)}$
* $v_{boat/water} = 5 \text{ m/s}$
* **Target:** Resultant velocity must be due North ($x$-component = 0).

Let the boat head at angle $\phi$ West of North.
$x$-component: $5 \sin(\phi) = 2 \implies \sin(\phi) = 0.4$.
**Angle:** $\phi = \arcsin(0.4) \approx \mathbf{23.6^\circ \text{ West of North}}$.

**Crossing time:** Use the Northward component of speed.
$v_{north} = 5 \cos(23.6^\circ) \approx 4.58 \text{ m/s}$.
$t = \frac{200 \text{ m}}{4.58 \text{ m/s}} \approx \mathbf{43.6 \text{ seconds}}$.

---

## 6. Variable Velocity

$v(t) = t^2 + 2t - 5$, $x(0) = 4$.

* **Acceleration at $t=3$:**
$a(t) = \frac{dv}{dt} = 2t + 2$.
$a(3) = 2(3) + 2 = \mathbf{8 \text{ m/s}^2}$.
* **Position at $t=3$:**
$x(t) = \int (t^2 + 2t - 5) dt = \frac{1}{3}t^3 + t^2 - 5t + C$.
Since $x(0) = 4$, then $C = 4$.
$x(3) = \frac{1}{3}(27) + (9) - 5(3) + 4 = 9 + 9 - 15 + 4 = \mathbf{7}$.

---

## 7. Elimination of Time

$x = 2t^2, y = 3t^3$

* **Trajectory:** $t = \sqrt{x/2}$. Substitute into $y$:
$\mathbf{y = 3(x/2)^{3/2}}$ or $y^2 = \frac{27}{8}x^3$.
* **Vectors:**
* $\vec{v}(t) = (4t)\hat{i} + (9t^2)\hat{j} \implies |\vec{v}| = \sqrt{16t^2 + 81t^4}$
* $\vec{a}(t) = (4)\hat{i} + (18t)\hat{j} \implies |\vec{a}| = \sqrt{16 + 324t^2}$


* **Is acceleration constant?**
**No**, the $\hat{j}$ component ($18t$) depends on time.

---

## 8. Circular Motion

**Equator Centripetal Acceleration:** $a_c = \omega^2 R$.

* $R = 6.378 \times 10^6 \text{ m}$.
* $\omega = \frac{2\pi}{24 \times 3600} \approx 7.27 \times 10^{-5} \text{ rad/s}$.
* $a_c = (7.27 \times 10^{-5})^2 \times (6.378 \times 10^6) \approx \mathbf{0.034 \text{ m/s}^2}$.
(This is why you weigh slightly less at the equator!)

---

## 9. Momentum Comparison

$p = mv$ (Convert mass to kg!)

* **Fly:** $0.002 \text{ kg} \times 10 \text{ m/s} = \mathbf{0.02 \text{ kg}\cdot\text{m/s}}$.
* **Tennis Ball:** $0.060 \text{ kg} \times 1 \text{ m/s} = \mathbf{0.06 \text{ kg}\cdot\text{m/s}}$.
The **tennis ball** has greater momentum.

---

## 10. Kinematics (The Helix)

$\vec{r}(t) = (a \cos(\omega t), b \sin(\omega t), bt)$

a) **Trajectory:** In the $xy$-plane: $(\frac{x}{a})^2 + (\frac{y}{b})^2 = \cos^2(\omega t) + \sin^2(\omega t) = 1$.
This is an **elliptical cylinder**. Since $z = bt$ increases linearly, the path is an **elliptical helix**.

b) **Path Length ($s$):**
$v_x = -a\omega \sin(\omega t), v_y = b\omega \cos(\omega t), v_z = b$.
$|\vec{v}| = \sqrt{a^2\omega^2\sin^2(\omega t) + b^2\omega^2\cos^2(\omega t) + b^2}$.
If $a=b$, $|\vec{v}| = \sqrt{a^2\omega^2 + a^2} = a\sqrt{\omega^2+1}$ (Constant).
$s = \int_0^{t_0} |\vec{v}| dt$.

c) **Interactive Trajectory:**
If $a=b$, it’s a standard circular helix. If $a \neq b$, it's "squashed."

Would you like me to write the Python code to visualize this elliptical helix for you?