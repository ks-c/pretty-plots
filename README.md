# 📊 Pretty-Plots

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
！[HTML5]（https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white）  
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Plotly.js](https://img.shields.io/badge/Plotly.js-3F4F75?style=flat-square&logo=plotly&logoColor=white)

It is a repository of plotting scripts built with simple JS and HTML. It requires zero configuration, relies on no backend servers, and could be launched easily on any platform. Your data never leaves your browser, ensuring 100% privacy.

🌐 **[👉 Click here to visit the Live Preview on GitHub Pages](https://ks-c.github.io/pretty-plots/)**

---

## 🎨 Interface Overview

The tools in this repository share a unified, user-friendly interface designed for academic and professional use:

*   **Left Panel (Control Panel):** 
    *   **Data Source:** Upload your `.csv` or `.xlsx` files.
    *   **Variable Mapping:** Select which columns correspond to the X-axis, Y-axis, or groups.
    *   **Styling Engine:** Adjust publication-level parameters such as canvas size (e.g., standard Nature single-column width), font families (Arial, Times New Roman), font sizes, border thickness, and color palettes.
*   **Right Panel (Interactive Canvas):** 
    *   Real-time preview of your plots.
    *   **Interactive Editing:** Double-click on titles, axis labels, or annotations to edit them directly. Drag and drop specific elements (like significance brackets) for perfect alignment.
    *   **Export:** Download in high-resolution **PNG** or vector **SVG** (ready for PDF conversion) with one click.

---

## 🚀 Available Plots

All plot scripts are located in the `plot/` directory. You can access them via the index page or navigate to them directly.

### 🎻 1. Single-Class Violin Plot with Significance
**File:** [`plot/violin-single-class.html`](plot/violin-single-class.html)

A powerful tool to generate publication-ready violin plots with internal boxplots. 
*   **Auto-Statistics:** Automatically calculates Welch's t-test for pairwise comparisons and estimates P-values.
*   **Interactive Brackets:** Significance brackets (with auto-superscript stars like `***`) are fully draggable. You can freely adjust their height, line style (solid/dash), and thickness directly on the canvas.
*   **Customizable Bounds:** Supports full mirror bounding boxes and customizable gridlines.

### 🕸️ 2. Network Node Centrality Plot
**File:** [`plot/node-centrality.html`](plot/node-centrality.html)

Designed specifically for Network Analysis, allowing researchers to visualize node measures like *Betweenness*, *Closeness*, *Strength*, and *Expected Influence*.
*   **Multi-Dataset Support:** Upload multiple files at once to compare different profiles (e.g., High-risk vs. Low-risk groups) in a single plot.
*   **Batch Plotting:** Select multiple measures to generate several plots simultaneously.
*   **Advanced Layouts:** 
    1.  **Independent Plots:** Generates completely separate plots for each measure.
    2.  **Facet Grid (Subplots):** Aligns all measures side-by-side, sharing a single Y-axis (Node names) for an elegant, highly comparative academic layout.

---

## 🛠️ How to run locally

Since this project uses pure Frontend technologies, you don't need Node.js, Python, or any local servers.

1. Clone or download this repository.
2. Open the `index.html` or any script in the `plot/` folder directly in your modern web browser (Chrome, Edge, Safari, Firefox).
3. Start plotting!

## 📄 License
This project is open-source and available under the MIT License.
