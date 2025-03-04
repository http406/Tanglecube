# Tanglecube

### **What is a Tanglecube?**  
A **Tanglecube** is a type of **implicit surface** in mathematics and 3D geometry. It is defined by a specific algebraic equation, which generates a fascinating 3D shape resembling a deformed cube with curved indentations. Unlike a perfect cube, the Tanglecube has a more intricate and organic structure, making it visually interesting for mathematical visualizations.

This shape is studied in **computational geometry, implicit surfaces, and mathematical art**. By plotting thousands of points that satisfy the given equation, we can visualize its 3D form.

---

### **Understanding the Tanglecube Equation**
The equation used in your code is:

![Image](https://github.com/user-attachments/assets/1189ec16-32fd-459f-a418-9cb2acda8ee2)

This is an implicit equation that defines the shape. Let's break it down:

#### **1. Individual Terms (Power of 4 and Power of 2)**
- The terms **\(x⁴, y⁴, z⁴\)** create a **rounded shape**, similar to a superquadric.
- The terms **\(-5x², -5y², -5z²\)** introduce indentations in the cube, preventing it from being a smooth sphere.
- The constant **\(+11.8\)** determines the overall size and scale of the shape.

#### **2. The Effect of Different Terms**
- **\(x² - 5x²\)**: Controls how the shape behaves along the X-axis.  
  - When \( x \) is small, \( x⁴ \) dominates, making the shape rounded.
  - When \( x \) is large, the \(-5x²\) term counteracts growth, leading to indentations.
- **\(y⁴ - 5y²\)** and **\(z⁴ - 5z²\)**: The same behavior applies along the Y and Z axes.
- The sum of these terms creates a **deformed, tangle-like cube**.

#### **3. Why Does This Work?**
The equation defines a set of points **(x, y, z)** that satisfy the given condition. By sampling many random points and keeping only those that satisfy the equation (or are close to zero), the 3D structure appears.

---

### **Visually Appealing**
- The shape has a **symmetrical yet complex** structure, making it look organic and abstract.
- The **power of 4 and power of 2** terms create smooth curves and indentations.
- The **gradient colors** enhance its aesthetic appeal.


