# 🧩 Sudoku Solver KNN-Based App  

A powerful and accurate Sudoku Solver that uses K-Nearest Neighbors (KNN) for digit recognition. The app intelligently detects Sudoku grids from images, recognizes digits using machine learning, and solves the puzzles efficiently.  

---

## ✨ Features  

- 🔍 **Grid Detection:** Automatically identifies Sudoku grids from image inputs, even under varying brightness and noise conditions.  
- 🤖 **KNN-Based Digit Recognition:** Utilizes Histogram of Oriented Gradients (HOG) features and K-Nearest Neighbors for accurate digit classification.  
- ⚡ **High Accuracy:** Achieves a remarkable **96.96% accuracy** for digit recognition on test data.  
- 🧠 **Dataset Training:** Combines MNIST and TMNIST datasets for robust model training.  
- 🎯 **User-Friendly Interface:** Simple and straightforward interface for solving puzzles from images.  

---

## 🚀 Model Performance  

- **Test Accuracy:** **96.96%**  
- **Training Dataset:** A combination of MNIST and TMNIST datasets  
- **Feature Extraction:** HOG (Histogram of Oriented Gradients)  

---

## 📸 Screenshot  

![image](https://github.com/user-attachments/assets/cfa848a9-3624-4c88-bd8e-7d395816b7ba)
![image](https://github.com/user-attachments/assets/6877d811-aea2-410c-be03-a0cdf09793e6)
![image](https://github.com/user-attachments/assets/fc41fca8-32dc-4b46-a140-762118d0e91b)
![image](https://github.com/user-attachments/assets/1b2dc9b2-926c-4b84-9229-1b4da6b6b634)

 
*The app detecting a Sudoku grid, recognizing digits, and solving the puzzle efficiently.*

---

## 🛠️ Installation  

1. **Clone the repository:**  
   ```bash
   git clone https://github.com/AhmedZahran02/Sudoku-Solver-KNN-Based-App.git
   cd Sudoku-Solver-KNN-Based-App
   ```

2. **Install dependencies:**  
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Sudoku Solver:**  
   ```bash
   python main.py
   ```

---

## 🧑‍💻 Usage  

1. Provide the path to an image containing a Sudoku puzzle.
2. The app will:  
   - Detect the Sudoku grid.
   - Recognize the digits.
   - Solve the puzzle and display the solution.

---

## 📊 Accuracy Metrics  

| Metric          | Value   |
|-----------------|---------|
| **Model Type**   | KNN     |
| **Test Accuracy**| 96.96%  |
| **Features Used**| HOG     |

---

## 📦 Dependencies  

- **Core Libraries:**  
  - `numpy`
  - `scikit-image`
  - `opencv-python`
  - `scikit-learn`
  - `matplotlib`  

Install them using:
```bash
pip install -r requirements.txt
```

---

## 🔧 How It Works  

1. **Preprocessing:**  
   - Convert the image to grayscale.
   - Apply thresholding to enhance contrast.
   - Detect and extract the Sudoku grid.  

2. **Digit Recognition:**  
   - Extract digit regions and compute HOG features.
   - Use K-Nearest Neighbors (KNN) to classify digits.  

3. **Puzzle Solving:**  
   - Apply backtracking to solve the recognized Sudoku grid.

---

## 🎯 Future Improvements  

- Integration with a CNN model for even higher accuracy.  
- Web-based interface for remote puzzle-solving.  
- Improved grid detection for distorted images.

---

## 🏆 Acknowledgments  

- MNIST and TMNIST datasets for training.  
- OpenCV and scikit-learn for image processing and model training.  

---
