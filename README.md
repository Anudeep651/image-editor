# 🖼️ Browser-Based Image Editor

A simple and interactive **browser-based image editor** built using **HTML, CSS, and JavaScript**, leveraging the power of the **Canvas API (`canvasCtx`)** for real-time image processing.

This project allows users to upload an image, apply filters and presets, and download the edited result — all directly in the browser without any external libraries.

---

## 🚀 Features

* 📂 **Upload Image**
  Choose any image from your device and render it on canvas.

* 🎛️ **Adjustable Filters**

  * Brightness
  * Contrast
  * Saturation
  * Hue Rotation
  * Blur
  * Grayscale
  * Sepia
  * Opacity
  * Invert

* 🎨 **Preset Filters**

  * Normal
  * Drama
  * Vintage
  * Old School
  * Cinematic
  * Cool
  * Warm
  * Noir
  * Faded
  * Dreamy

* 🧠 **Canvas-Based Processing**

  * Uses **`canvasCtx` (CanvasRenderingContext2D)**
  * Real-time rendering of filters
  * Efficient pixel manipulation and drawing

* 🔄 **Reset Option**
  Restore all filters to default values instantly.

* 💾 **Download Image**
  Export the edited image directly from canvas.

---

## 🛠️ Tech Stack

* **HTML** – Structure
* **CSS** – Styling
* **JavaScript** – Logic & interactivity
* **Canvas API (`canvasCtx`)** – Image rendering & manipulation

---

## 📸 How It Works

1. Upload an image.
2. The image is drawn onto a canvas using `canvasCtx.drawImage()`.
3. Filters are applied dynamically using CSS filter strings or canvas manipulation.
4. Presets apply predefined filter values.
5. Final image is exported using `canvas.toDataURL()`.

---

## 📁 Project Structure

```id="b7e3d2"
/image-editor
│── index.html
│── style.css
│── script.js
│── theme.css
```

---

## 🙌 Acknowledgment

Built as a hands-on project to learn **Canvas API**, image manipulation, and frontend development.

---
