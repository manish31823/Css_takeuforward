# 🌟 Glass Effect CSS Implementation

This project demonstrates a **Glassmorphism (Frosted Glass Effect)** in CSS, inspired by Figma’s design style.  
The implementation is **lightweight, reusable, and requires only 2 classes**, making it easy to apply on any `<div>`.

---

## ✅ Requirements Fulfilled
- Resembles **Figma’s frosted/blurred glass effect**  
- **No hardcoded borders** → adaptive via `rgba()`  
- **No masking techniques** used  
- **Maximum 2 CSS classes** for universal application  

---

## 🖼️ Demo Preview
![Glass Effect Demo]("C:\Users\Manish Chaudhary\OneDrive\Desktop\Glass Hero Section_Manish.html")

---

## 📂 Project Structure
Css_design/
│── index.html # Example usage of the glass effect
│── style.css # Glass effect CSS
│── thumbnail.png # Preview image
│── README.md # Documentation

---

## 🎨 Glass Effect CSS
```css
.glass {
  background: rgba(255, 255, 255, 0.15);
  backdrop-filter: blur(12px);
  -webkit-backdrop-filter: blur(12px);
  border-radius: 16px;
  border: 1px solid rgba(255, 255, 255, 0.3);
  box-shadow: 0 4px 30px rgba(0, 0, 0, 0.1);
  padding: 20px;
  color: #fff;
}

.center {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  background: url('your-background.jpg') no-repeat center center/cover;
}
