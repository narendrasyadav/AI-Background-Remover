# 🖼️ AI Background Remover with Sharpening & Download

This project is a **Gradio-based Jupyter Notebook app** that removes image backgrounds using [rembg](https://github.com/danielgatis/rembg) AI models.  
It allows you to:
- Upload an image
- Choose an AI model (`u2net`, `u2netp`, `u2net_human_seg`, `isnet-general-use`, `isnet-anime`)
- Optionally apply a **sharpening filter**
- Download the processed image with transparency preserved

---

## 🚀 Features
- 🔥 **AI-powered background removal** with multiple model options  
- ✨ **Optional sharpening** for crisp results  
- 📥 **Download processed images** with transparency (PNG)  
- 🌐 **Interactive Gradio UI** inside Jupyter/Colab  

---

## 📦 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/ai-background-remover.git
   cd ai-background-remover
   ```

2. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```

---

## 🛠️ Dependencies
This project uses the following Python libraries:
- [gradio](https://gradio.app/) – for the UI  
- [rembg](https://github.com/danielgatis/rembg) – for AI background removal  
- [Pillow (PIL)](https://pillow.readthedocs.io/) – for image manipulation  
- [numpy](https://numpy.org/) – for numerical operations  

---

## ▶️ Usage

### Run in Jupyter Notebook
1. Open the notebook:
   ```bash
   jupyter notebook AI_Background_Remover.ipynb
   ```

2. Run all cells.  
   A **Gradio app link** will appear – open it in your browser.  

3. Upload an image, select a model, choose sharpening if needed, and download the output.  

### Run in Google Colab (recommended)
- Upload the notebook to [Google Colab](https://colab.research.google.com/)  
- Install dependencies inside Colab:
  ```bash
  !pip install gradio rembg pillow numpy
  ```
- Run all cells and use the provided **public Gradio link**.  

---

## 📂 Project Structure
```
.
├── AI_Background_Remover.ipynb   # Main Jupyter Notebook
├── requirements.txt              # Project dependencies
├── README.md                     # Project documentation
```

---

## 🔮 Demo (Screenshots)
*(You can add screenshots here after running the notebook)*  

---

## 📜 License
This project is licensed under the **MIT License** – feel free to use, modify, and share.  

---

## 🙌 Acknowledgements
- [rembg](https://github.com/danielgatis/rembg) for the background removal engine  
- [Gradio](https://gradio.app/) for the UI framework  
- [Pillow](https://pillow.readthedocs.io/) for image manipulation  
