# 🧮 Manim Math Visualization Generator

> **Transform math concepts into stunning animations using the power of AI and Manim.**

![Python Version](https://img.shields.io/badge/python-3.7+-blue.svg)


## 📚 Overview

The **Manim Math Visualization Generator** is a powerful, AI-assisted tool that bridges the gap between mathematical ideas and beautiful animations. By combining [Manim](https://www.manim.community/)—the leading engine for mathematical animations—with Google’s **Gemini AI**, you can generate professional-quality visuals from simple text descriptions.
**NOTE**  THIS PROJECT IS CURRENTLY IN A **EXPERIMENTAL** STAGE.USE WITH CAUTION.

### Ideal for:
- 👩‍🏫 **Teachers** explaining complex concepts visually  
- 👨‍🎓 **Students** creating engaging study material  
- 💻 **Content creators** building educational content  
- 🧪 **Researchers** visualizing theoretical models  


## ✨ Features

- 🤖 **AI-Powered Conversion**: Turns math descriptions into Manim Python code  
- 🎬 **High-Quality Animations**: Professional-grade rendering using Manim  
- 🖱️ **No Coding Required**: Intuitive interface—just type and visualize  
- 📥 **Video Export**: Save animations for use in slides, videos, or lessons  
- 🔗 **Google Gemini Integration**: Powered by advanced generative AI  


## 🛠️ Installation & Setup

### ✅ Prerequisites

- Python 3.7+
- Internet connection (for AI capabilities)
- A Google Gemini API Key → [Get yours here](https://aistudio.google.com/)

### ⚡ Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/manim-math-visualizer.git
   cd manim-math-visualizer
   ```

2. **Run the setup script**
   ```bash
   python setup.py
   ```

   This will:
   - Install all required dependencies (Manim, Pillow, Gemini SDK, etc.)
   - Configure FFmpeg and Cairo for rendering
   - Set up a virtual environment
   - Generate launch scripts

3. **Launch the App**
   - **Windows**: Double-click `main.py`
   - **macOS/Linux**: Run `./main.py` in the terminal

4. **Enter your Gemini API key** on first launch


## 🖥️ How to Use

1. **Describe your math concept**
   ```
   Examples:
   - Show a geometric proof of the Pythagorean theorem
   - Visualize the convergence of sin(x) using its Taylor series
   - Illustrate a derivative as the limit of secant slopes
   ```

2. **Click “Generate Visualization”**
   - The AI will interpret and refine your prompt
   - Generate Manim code
   - Render and preview the animation

3. **Review Output**
   - Watch the animation instantly
   - Access the Manim code used
   - Find the video in `media/videos/`


## ⚙️ Configuration & Settings

### 🔐 Change Your API Key

1. Click the **⚙️ Settings** icon
2. Select **"Change API Key"**
3. Enter your new Gemini key


## 💻 System Requirements

| Component | Minimum | Recommended |
|-----------|---------|-------------|
| **CPU**   | Dual-core | Quad-core or better |
| **RAM**   | 4GB       | 8GB+                |
| **Storage**| 1GB free | 5GB+ free           |
| **OS**    | Windows 10+, macOS 10.14+, Ubuntu 18.04+ | Latest versions |


## 🚧 Planned Features

- [ ] Advanced Manim customization options
- [ ] Export in various formats & resolutions
- [ ] Built-in library of animations & templates
- [ ] Collaborative visualization sharing
- [ ] LMS integration (e.g., Moodle, Canvas)
- [ ] One-click YouTube upload


## 🧰 Troubleshooting

### ⚠️ FFmpeg Not Found
- Make sure FFmpeg is installed and added to your system’s `PATH`
- Restart the application after installation

### 🔐 API Key Issues
- Confirm your Gemini API key is valid and active
- Ensure you're connected to the internet
- Check your API quota limits


## 🤝 Contributing

We welcome contributions of all kinds—feature suggestions, bug fixes, or documentation improvements.

> To contribute:
> 1. Fork the repository  
> 2. Create a new branch (`feature/your-feature`)  
> 3. Commit your changes  
> 4. Submit a pull request


## 🙏 Acknowledgments

- [Manim Community](https://www.manim.community/) – for the amazing animation engine
- [Google Gemini](https://deepmind.google/technologies/gemini/) – for powering the AI
