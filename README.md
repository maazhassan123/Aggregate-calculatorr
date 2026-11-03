# 🎓 ECAT Aggregate Calculator

A modern, fast, and responsive web application designed to calculate the admission aggregate for Engineering College Admission Test (**ECAT**) candidates (such as UET Lahore and affiliated universities).

---

## ✨ Features

- **⚡ Instant Aggregate Calculation:** Computes your final admission aggregate accurate to 3 decimal places in real-time.
- **📊 Individual Contribution Breakdown:** Visualizes the exact percentage contribution of Matric, FSc Part 1, and ECAT marks.
- **🛡️ Built-in Input Validation:** Validates empty fields, numerical limits, maximum mark boundaries, and negative numbers with clear user feedback.
- **🎨 Modern Glassmorphism & UI Design:** Styled with sleek gradients, subtle glassmorphism, responsive cards, and clean typography using Google's *Plus Jakarta Sans*.
- **📱 Fully Responsive:** Optimized for desktop screens, tablets, and mobile devices.
- **⌨️ Keyboard Shortcut Support:** Press <kbd>Enter</kbd> from any field to calculate instantly.
- **🔄 One-Click Reset:** Clear all inputs and results with a single click.

---

## 🧮 Aggregate Calculation Formula

The aggregate is evaluated based on the following standard weightage distribution:

| Criteria | Total Marks | Weightage | Calculation Formula |
| :--- | :---: | :---: | :--- |
| **Matriculation** | 1100 | **17%** | `(Marks Obtained / 1100) × 17` |
| **FSc / Inter (Part-1)** | 570 | **50%** | `(Marks Obtained / 570) × 50` |
| **ECAT** | 400 | **33%** | `(Marks Obtained / 400) × 33` |
| **Total Aggregate** | - | **100%** | **Sum of all 3 contributions** |

$$\text{Aggregate} = \left(\frac{\text{Matric}}{1100} \times 17\right) + \left(\frac{\text{Part 1}}{570} \times 50\right) + \left(\frac{\text{ECAT}}{400} \times 33\right)$$

---

## 🚀 Getting Started

No build tools, dependencies, or package installations are required!

### 1. Clone or Download the Repository
```bash
git clone https://github.com/your-username/Aggregate-calculatorr.git
cd Aggregate-calculatorr
```

### 2. Run the Calculator
Simply open `index.html` in any modern web browser:
- Double click on `index.html`, **or**
- Right-click and choose **Open With > Google Chrome / Microsoft Edge / Firefox / Safari**.

---

## 🛠️ Tech Stack

- **HTML5:** Semantic structure and accessible form controls.
- **CSS3:** Modern CSS variables, flexbox, grid, glassmorphism backdrop filters, and CSS keyframe animations.
- **JavaScript (ES6):** Client-side validation, formula calculation, and DOM manipulation.

---

## ⚙️ Customization

If your board or institution uses different total marks (e.g., FSc Part 1 out of 520 or 505, or different percentage weightages), you can adjust the values in [`index.html`](file:///d:/amendments%20in%20github%20reos/Aggregate-calculatorr/index.html):

```javascript
// Inside the maaz() function in index.html:
const matricContrib = (m / 1100) * 17;   // Adjust 1100 or 17
const part1Contrib = (p1 / 570) * 50;    // Adjust 570 or 50
const ecatContrib = (ecat / 400) * 33;   // Adjust 400 or 33
```

---

## 📄 License

This project is open source and free to use for personal and educational purposes.
