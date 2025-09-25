# Image to Pencil Sketch 🎨✏️

This repository demonstrates how to transform an image into a pencil sketch using **Python** and **OpenCV**. The process involves converting the image to grayscale, inverting it, blurring it, and blending to create a sketch-like effect.  

## 📌 Features
- Load and display an image.  
- Convert image to grayscale.  
- Invert grayscale image.  
- Apply Gaussian blur.  
- Blend images using dodge blend to create a pencil sketch.  

## ⚙️ Requirements
Install the required dependencies:  
```bash
pip install opencv-python matplotlib
```

## 🚀 Usage
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/Image-to-Pencil-Sketch.git
   cd Image-to-Pencil-Sketch
   ```
2. Open the notebook:
   ```bash
   jupyter notebook Image_to_Pencil_Sketch.ipynb
   ```
3. Update the image path inside the notebook:
   ```python
   path = './datasets/dog.jpg'  # Change to your image path
   ```
4. Run all cells in order to generate the pencil sketch.  

## 📂 Project Structure
```
Image-to-Pencil-Sketch/
│── datasets/                     # Folder for input images
│   └── dog.jpg                   # Example image
│── Image_to_Pencil_Sketch.ipynb  # Jupyter Notebook
│── README.md                     # Documentation
```

## 🖼️ Example Workflow
1. **Original Image**  
2. **Grayscale Conversion**  
3. **Inverted Image**  
4. **Blurred Image**  
5. **Final Pencil Sketch**  

*(Insert example screenshots here)*  

## 🤝 Contributing
Contributions are welcome! If you’d like to add improvements (e.g., GUI, batch processing, CLI tool), feel free to fork the repo and submit a PR.  

## 📜 License
This project is licensed under the MIT License.  
