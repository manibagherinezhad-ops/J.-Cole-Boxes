# 🎵 J. Cole's Boxes

> A visual front-end experiment featuring four interactive J. Cole album-era boxes built with **HTML & CSS**.

---

## 🖤 About The Project

**J. Cole's Boxes** is a small front-end project created to experiment with **visual composition, Flexbox layouts, hover interactions, overlays, and CSS transitions**.

The page presents four square images representing different eras of J. Cole's music:

* 🎵 **The Fall-Off Era**
* 👁️ **4 Your Eyez Only Era**
* 🔥 **The Off-Season Era**
* 🖤 **Born Sinner Era**

Each box contains an image, a dark overlay, and a caption surrounded by decorative lines. When the user hovers over a box, the overlay becomes visible and the caption rotates while its decorative lines expand.

The project focuses on creating an interactive visual experience with **HTML and CSS**, without relying on JavaScript.

---

## 🌐 Live Demo

🎵 **[View the Live Website](https://manibagherinezhad-ops.github.io/J.-Cole-Boxes/)**

---

## 🎴 Features

* 🎵 **Four J. Cole Album Eras**
  The interface presents four visual boxes representing different eras: The Fall-Off, 4 Your Eyez Only, The Off-Season, and Born Sinner.

* 🖼️ **Image-Based Composition**
  Each box uses a dedicated J. Cole image positioned inside a fixed square container.

* 🖱️ **Hover Interaction**
  Hovering over each box changes the opacity of its dark overlay and activates the caption styling.

* 🌑 **Dark Image Overlay**
  A black overlay is placed above each image and smoothly fades in when the user hovers over the box.

* ✍️ **Interactive Captions**
  Each caption rotates in a different direction depending on the box, creating visual variation across the composition.

* 📏 **Decorative Line Animation**
  The horizontal lines surrounding each caption scale on hover, creating a subtle interactive effect.

* 📐 **Flexbox Layout**
  The four boxes are centered inside a full-screen `figure` using Flexbox with spacing between the elements.

* ⚡ **No JavaScript**
  The interactions are handled through HTML and CSS hover states.

---

## 🛠️ Built With

* 🌐 **HTML5**
* 🎨 **CSS3**
* 📦 **Flexbox**
* 🖱️ **CSS `:hover`**
* 🌑 **CSS Opacity**
* 🎞️ **CSS Transitions**
* 📐 **CSS Positioning**
* 🌈 **CSS Gradients**

---

## 📂 Project Structure

```text
J-Cole-Boxes/
│
├── index.html
│
├── assets/
│   ├── css/
│   │   ├── public.css
│   │   └── master.css
│   │
│   └── images/
│       ├── JCole1.png
│       ├── JCole2.png
│       ├── JCole3.png
│       └── JCole4.png
│
└── README.md
```

## The HTML page loads both `public.css` and `master.css`, while the four visual boxes use the corresponding J. Cole images from the `assets/images` directory.

## 🌀 How It Works

The main layout is built around a `figure` element that fills the viewport:

```css
figure {
    width: 100%;
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 20px;
}
```

This creates a centered horizontal composition for the four image boxes.

Each box is given a fixed `350px × 350px` size and uses `position: relative` so that the image, overlay, and caption can be layered together.

The images themselves fill their containers using:

```css
img {
    position: absolute;
    width: 100%;
    height: 100%;
    object-fit: cover;
}
```

This keeps the images contained within their square boxes while maintaining their cover behavior.

---

## 🖱️ Hover Interaction

The main interaction happens when the user hovers over one of the boxes.

The dark overlay starts with:

```css
opacity: 0;
```

and changes to:

```css
opacity: 0.5;
```

on hover. A transition creates the gradual fade between the two states.

At the same time, the caption rotates.

For example, the first box uses:

```css
transform: rotate(-30deg);
```

while the second box uses:

```css
transform: rotate(30deg);
```

## This gives the four boxes slightly different visual directions instead of making every interaction identical.

## 📐 CSS Techniques

This project was created to practice several CSS techniques:

* `display: flex`
* `justify-content`
* `align-items`
* `gap`
* `position: relative`
* `position: absolute`
* `object-fit`
* `opacity`
* `transition-duration`
* `transition-delay`
* `transform`
* `rotate()`
* `scaleX()`
* `transform-origin`
* `:hover`
* CSS custom properties
* `radial-gradient()`

The decorative caption lines also use different `transform-origin` values so that they expand from different directions during the hover interaction.

---

## 🎯 Purpose

This project was created as a **front-end practice project** to improve skills in:

* HTML structure
* Flexbox layout
* CSS positioning
* Hover interactions
* CSS transitions
* Image overlays
* Opacity effects
* Transformations
* Pseudo-elements and nested CSS selectors
* Visual composition
* Interactive UI design

The main goal was to create a visually interesting interface using a relatively small amount of HTML and CSS.

---

## 🎨 Design Direction

The design uses a dark navy background with subtle radial gradients and a four-card composition.

The background combines several radial gradients with a dark navy base, while the cards remain the main visual focus.

Each image is intentionally presented as a square element, while the caption and decorative lines sit above the image and become more prominent during interaction.

The result is a compact visual experiment built around **images, spacing, contrast, rotation, and hover behavior**.

---

## 👨‍💻 Author

### Mani Bagherinezhad

**Front-End Developer**

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge\&logo=github\&logoColor=white)](https://github.com/manibagherinezhad-ops)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge\&logo=linkedin\&logoColor=white)](https://www.linkedin.com/in/mani-bagherinezhad-641217350/)

[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge\&logo=instagram\&logoColor=white)](https://www.instagram.com/manibagherinezhad_dev/)

---

## 🧑‍🏫 Mentor

### Parsa Ghorbanian

**Mentor**

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge\&logo=github\&logoColor=white)](https://github.com/parsaGhorbanian)

[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge\&logo=instagram\&logoColor=white)](https://www.instagram.com/parsa_ghorbanian_web/)

[![Web Design Course](https://img.shields.io/badge/Web_Design_Course-4285F4?style=for-the-badge\&logo=google-chrome\&logoColor=white)](https://trainingsitedesign.ir/learn-web-design/)

---

## ⚠️ Disclaimer

This project is created for **educational and portfolio purposes**.

The J. Cole-related images and artwork used in the project belong to their respective creators and copyright holders.

This project is a fan-made front-end practice project and is not affiliated with or endorsed by J. Cole or his representatives.

---

### 🎵 *Four eras. Four boxes. One visual experience.*

**Made with HTML, CSS & 🎵**
