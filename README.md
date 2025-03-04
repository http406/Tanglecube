# Tanglecube

### **What is a Tanglecube?**  
A **Tanglecube** is a type of **implicit surface** in mathematics and 3D geometry. It is defined by a specific algebraic equation, which generates a fascinating 3D shape resembling a deformed cube with curved indentations. Unlike a perfect cube, the Tanglecube has a more intricate and organic structure, making it visually interesting for mathematical visualizations.

This shape is studied in **computational geometry, implicit surfaces, and mathematical art**. By plotting thousands of points that satisfy the given equation, we can visualize its 3D form.

---

### **Understanding the Tanglecube Equation**
The equation used in your code is:

\[
x^4 - 5x^2 + y^4 - 5y^2 + z^4 - 5z^2 + 11.8 = 0
\]

This is an implicit equation that defines the shape. Let's break it down:

#### **1. Individual Terms (Power of 4 and Power of 2)**
- The terms **\(x^4, y^4, z^4\)** create a **rounded shape**, similar to a superquadric.
- The terms **\(-5x^2, -5y^2, -5z^2\)** introduce indentations in the cube, preventing it from being a smooth sphere.
- The constant **\(+11.8\)** determines the overall size and scale of the shape.

#### **2. The Effect of Different Terms**
- **\(x^4 - 5x^2\)**: Controls how the shape behaves along the X-axis.  
  - When \( x \) is small, \( x^4 \) dominates, making the shape rounded.
  - When \( x \) is large, the \(-5x^2\) term counteracts growth, leading to indentations.
- **\(y^4 - 5y^2\)** and **\(z^4 - 5z^2\)**: The same behavior applies along the Y and Z axes.
- The sum of these terms creates a **deformed, tangle-like cube**.

#### **3. Why Does This Work?**
The equation defines a set of points **(x, y, z)** that satisfy the given condition. By sampling many random points and keeping only those that satisfy the equation (or are close to zero), the 3D structure appears.

---

### **Why is it Visually Appealing?**
- The shape has a **symmetrical yet complex** structure, making it look organic and abstract.
- The **power of 4 and power of 2** terms create smooth curves and indentations.
- The **gradient colors** enhance its aesthetic appeal.

Would you like to tweak the equation to explore variations of the shape? 🚀
