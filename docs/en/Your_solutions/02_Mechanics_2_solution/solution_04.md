# Physics Problem Set Solutions

## 1. The Sliding Block & Collision

**Problem:** A 0.5 kg block slides down from 3.0 m and sticks to a 1.5 kg block at rest. Find the final speed.

### Step 1: Find the speed at the bottom (Energy Conservation)
The potential energy ($mgh$) at the top is converted to kinetic energy ($\frac{1}{2}mv^2$) at the bottom.

$$

mgh = \frac{1}{2}mv^2

$$

Solving for $v$ (mass cancels out):

$$

v = \sqrt{2gh}

$$

Using $g = 9.8$ and $h = 3.0$:

$$

v = \sqrt{2 \cdot 9.8 \cdot 3.0} = \sqrt{58.8} \approx 7.67 \, \text{m/s}

$$

### Step 2: Find the combined speed (Momentum Conservation)
Since the blocks stick together, we use the inelastic collision formula. Let $m_1 = 0.5$, $v_1 = 7.67$, $m_2 = 1.5$, and $v_2 = 0$.

$$

m_1v_1 + m_2v_2 = (m_1 + m_2)v_f

$$

$$

(0.5 \cdot 7.67) + (1.5 \cdot 0) = (0.5 + 1.5)v_f

$$

$$

3.835 = 2.0 \cdot v_f

$$

$$

v_f = \frac{3.835}{2.0} = 1.9175 \approx 1.92 \, \text{m/s}

$$

**Final Speed:** 1.92 m/s

---

## 2. Simple Pendulum Calculations

### A. Gravitational Dependence (Moon vs. Earth)
**Problem:** $T_{Earth} = 4s$. Find $T_{Moon}$ where $g_{Moon} = \frac{1}{6}g_{Earth}$.

From the formula $T = 2\pi\sqrt{\frac{L}{g}}$, we see that $T \propto \frac{1}{\sqrt{g}}$.

$$

\frac{T_{Moon}}{T_{Earth}} = \frac{\sqrt{g_{Earth}}}{\sqrt{g_{Moon}}}

$$

Since $g_{Moon} = \frac{g_{Earth}}{6}$:

$$

\frac{T_{Moon}}{4} = \sqrt{6}

$$

$$

T_{Moon} = 4 \cdot \sqrt{6} \approx 4 \cdot 2.45 \approx 9.80 \, \text{s}

$$

**Period on Moon:** 9.80 seconds.

### B. Required Length for $T = 1s$
**Problem:** Find $L$ when $T = 1.0$ and $g = 9.8$.

Using the period formula:

$$

1 = 2\pi\sqrt{\frac{L}{9.8}}

$$

Divide by $2\pi$:

$$

\frac{1}{2\pi} = \sqrt{\frac{L}{9.8}}

$$

Square both sides:

$$

\frac{1}{4\pi^2} = \frac{L}{9.8}

$$

$$

L = \frac{9.8}{4\pi^2} \approx \frac{9.8}{39.48} \approx 0.248 \, \text{m}

$$

**Required Length:** 24.8 cm
