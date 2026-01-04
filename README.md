# 👔 AI Fashion 3D Collection: Modern Tech-Tailoring

Welcome to the **"Modern Classic with Tech-Tailoring"** 3D fashion collection. This project showcases a high-fidelity, seasonal wardrobe designed for the modern 50-year-old man, optimized for seamless **WebAR** experiences.

## ✨ Project Highlights
- **Target Persona:** East Asian male (173cm, 65kg) with an athletic swimmer's physique and a clean-shaven, professional look.
- **Design Concept:** A fusion of timeless classic silhouettes and cutting-edge technical performance fabrics.
- **Platform Compatibility:** Dual-format export ensures a premium experience across Android (GLB) and iOS (USDZ).

## 🚀 Optimized 3D Assets (WebAR Ready)
All models have been decimated by 50% (~11k polygons) and compressed with Draco to ensure ultra-fast loading (<2MB per file) on mobile devices via GitHub Pages.

| Season | Style | GLB (Android/Web) | USDZ (iOS Native) |
| :--- | :--- | :--- | :--- |
| **🌸 Spring** | Modern Grey Suit | [Download](./res/spring.glb) | [Download](./res/spring.usdz) |
| **☀️ Summer** | Tech-Polo & Loafers | [Download](./res/summer.glb) | [Download](./res/summer.usdz) |
| **🍂 Autumn** | Classic Trench Coat | [Download](./res/autumn.glb) | [Download](./res/autumn.usdz) |
| **❄️ Winter** | Technical Wool Coat | [Download](./res/winter.glb) | [Download](./res/winter.usdz) |

## 📱 WebAR Implementation
Deploy these models instantly using Google's `<model-viewer>`. This snippet automatically handles AR Quick Look on iOS and Scene Viewer on Android.

```html
<!-- Example: Summer Business Casual AR Placement -->
<model-viewer 
  src="summer.glb" 
  ios-src="summer.usdz" 
  ar 
  ar-modes="webxr scene-viewer quick-look" 
  camera-controls 
  touch-action="pan-y"
  shadow-intensity="1"
  exposure="1.2"
  alt="Modern 50s Summer Tech-Tailoring">
</model-viewer>
```

## 🛠 Tech Stack
- **AI Design:** Midjourney / Rodin (Hyper3D)
- **3D Modeling:** Blender 3.6+
- **Exporting:** glTF 2.0 (with Draco) & Universal Scene Description (USDZ)
- **Environment:** Antigravity AI Assistant

---
*Created for the High-End Fashion AR Digital Transformation project.*
