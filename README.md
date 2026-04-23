# Food Classifier 🍖🍗🐟

A simple client-side web application that uses a Teachable Machine image model to classify an image as **meat**, **chicken**, or **fish**. The entire inference runs in the browser with TensorFlow\.js—no backend required.

---

## 🔗 Live Demo

[https://YourUserName.github.io/food-classifier/](https://YourUserName.github.io/food-classifier/)

(Replace `YourUserName` with your GitHub username after deployment.)

---

## 📁 Project Structure

```
food-classifier/
├── index.html       # Main web page with drag & drop upload
├── model.json       # Teachable Machine model topology
├── metadata.json    # Labels and metadata
└── weights.bin      # Model weights
```

---

## 🚀 Getting Started

### Prerequisites

* A modern web browser (Chrome, Firefox, Edge, Safari)
* A local HTTP server (to serve files over `http://`, avoiding `file://` CORS issues)

### Installation & Running Locally

1. **Clone the repository**

   ```bash
   git clone https://github.com/YourUserName/food-classifier.git
   cd food-classifier
   ```

2. **Start a local server** (example using Python):

   ```bash
   python -m http.server 8000
   ```

3. **Open the app** in your browser:

   ```text
   http://localhost:8000
   ```

4. **Use it**: Click or drag & drop an image onto the page. The model will classify it and display confidence bars.

---

## 📦 Deployment on GitHub Pages

1. Push the `main` branch to GitHub.
2. In your repository settings → Pages, set **Source** to `main` branch, `/ (root)` folder.
3. Visit `https://YourUserName.github.io/food-classifier/` to see it live.

---




