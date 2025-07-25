# Arc-Length Reparameterization

This project demonstrates how to reparameterize a parametric curve `(x(t), y(t))` by arc length in order to achieve **uniform motion along the curve**. The notebook visualizes and compares two types of traversal:

- **Uniform steps in parameter `t`** (original curve)
- **Uniform steps in arc length `s`** (reparameterized for constant speed)

---

## 📌 Motivation

In applications such as motion control, computer graphics, and robotics, uniform stepping in a parameter `t` does not result in uniform physical motion. Instead, reparameterizing the curve by its arc length allows for **constant-speed traversal**.

This notebook was inspired by a reality check assignment from *Numerical Analysis (Sauer)* and shows how numerical integration and root-finding can be combined to solve this problem.

---

## 🧮 Topics Covered

- Arc length calculation using `scipy.integrate.quad`
- Root finding for arc length inversion using `scipy.optimize.root_scalar`
- Newton’s method for fast reparameterization
- Matplotlib animations for comparing traversal styles

---

## 🚀 How to Run

You can open and run the notebook in **Google Colab**:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/)

Make sure the following Python packages are available:
- numpy
- scipy
- matplotlib
- pandas

---

## 📽️ Preview

The notebook includes an animation that compares:
- Left: motion based on uniform `t`
- Right: motion based on uniform arc length `s`

It also draws trails behind each dot as they move across the curve.

---

## 📁 Files

- `arc_length_animation.ipynb`: Main notebook with code and animation
- `README.md`: This file

---

## 📚 References

- Sauer, T. *Numerical Analysis*
- [Reality Check 5 – Arc Length Animation](https://langou.github.io/4650/rc5/rc5.gif)

---

## ✍️ Author

Sarocha S. ([@sarochasi](https://github.com/sarochasi))

---

## 📝 License

MIT License
