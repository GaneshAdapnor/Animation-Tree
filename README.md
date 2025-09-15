# 🎄 Animated Christmas Tree

An interactive and beautifully animated SVG Christmas Tree built with **HTML**, **CSS**, and **JavaScript** using the **GSAP (GreenSock Animation Platform)** library.  

This project creates a magical holiday experience with glowing particles, animated ornaments, and a sparkling star. It’s a great example of using **SVG graphics + GSAP animations** for creative frontend projects.  

---

## ✨ Features
- 🌟 **SVG-based Christmas Tree** with smooth animations  
- 🎆 **Particle effects** (stars, hearts, circles, crosses) that move around dynamically  
- ✍️ **Path drawing animation** using GSAP’s `DrawSVGPlugin`  
- ⭐ **Star animation** with glow and bounce effect  
- 🎨 **Custom festive font** for text  
- 📱 Fully responsive (scales to screen size)  

## 📂 Project Structure

### 🔹 `index.html`
- Contains the **SVG tree structure**
- Defines gradients, masks, filters, and star
- Loads GSAP plugins from CDN
- Links to `style.css` and `script.js`

### 🔹 `style.css`
- Festive font: *Mountains of Christmas* 🎅  
- Background color: dark night sky 🌌  
- Centers the SVG on screen  
- Styles the message and links  

### 🔹 `script.js`
- Handles **all animations** using GSAP:
  - Converts shapes (`polygon`) to paths  
  - Creates particle effects with random physics  
  - Animates tree outline drawing  
  - Animates star and sparkle effects  
  - Controls timing with GSAP timelines 
git clone https://github.com/your-username/christmas-tree.git
cd christmas-tree
