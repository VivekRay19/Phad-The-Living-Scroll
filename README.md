# 📜 Phad: The Living Scroll

> *An immersive digital journey into the 700-year-old art of Phad Painting.*

**Phad: The Living Scroll** is an interactive storytelling experience that combines modern web technologies with traditional Indian heritage. It deconstructs the intricate details of Phad paintings using parallax scrolling, scroll-triggered animations, and an AI-powered cultural chatbot.

## 🚀 Features

### 🎨 Immersive Storytelling (Steps 1-8)
The experience is broken into 8 distinct chapters, each utilizing different animation techniques to mirror the creation process of a Phad painting:
* **Step 1 (Kharat):** Uses **GSAP Observer** to simulate the preparation of the canvas.
* **Step 3 (Nirman):** Features complex **Parallax Effects** to show layer depth.
* **Step 5 (Shringar):** A "Zoom & Fade" sequence that highlights intricate details.
* **Step 8 (Finale):** A particle-based ending sequence representing the eternal nature of the art.

### 🤖 "Ask Bhopa" Chatbot
* **Tech:** Built with **React.js**, **Framer Motion**, and **Tailwind CSS**.
* **Function:** Simulates a conversation with a traditional *Bhopa* (priest-singer), allowing users to ask context-aware questions about the history and folklore of Phad.

## 🛠️ Tech Stack
* **Core:** HTML5, CSS3, JavaScript (ES6+)
* **Animation Engine:** [GSAP](https://greensock.com/gsap/) (GreenSock Animation Platform)
    * *Plugins:* ScrollTrigger, Observer, TextPlugin
* **UI Frameworks:** React 18 (for Chatbot), Tailwind CSS
* **Motion:** Framer Motion

## 📂 Project Structure
```text
├── index.html       # The Curtain Raiser (Intro)
├── step1.html       # Kharat (Canvas Prep) - Observer-based scroll
├── step2.html       # Rang (Colors) - Color transitions
├── step3.html       # Nirman (Creation) - Parallax layering
├── step4.html       # Likhi (Writing) - Horizontal scroll triggers
├── step5.html       # Shringar (Decoration) - Zoom effects
├── step6.html       # Legacy - Stacked card animations
├── step7.html       # Tradition - 3D Carousel
├── step8.html       # Eternal Scroll - Particle finale
└── chatbot.html     # Ask Bhopa - React-based AI interface
