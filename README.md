# 🌸 Iris Binary Classification using Naive Bayes

This project demonstrates how to use the Gaussian Naive Bayes algorithm to perform binary classification on the famous Iris dataset. The model classifies whether a flower is **Setosa (1)** or **Not Setosa (0)** and visualizes performance using a confusion matrix heatmap.

---

## 🚀 Features

* Binary classification using Naive Bayes
* Uses Iris dataset (converted to 2 classes)
* Model evaluation (Accuracy, Confusion Matrix, Classification Report)
* Visualization using Seaborn heatmap
* Simple and beginner-friendly implementation

---

## 🛠️ Tech Stack

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn

---

## 📂 Project Structure

```id="proj-struct"
naive-bayes-iris-binary-classifier/
│
├── naive_bayes.py        # Main script
├── README.md             # Documentation
```

---

## ⚙️ How It Works

1. Load Iris dataset from online source
2. Convert multi-class labels into binary:

   * Setosa → 1
   * Others → 0
3. Split dataset into training and testing sets
4. Train Gaussian Naive Bayes model
5. Predict on test data
6. Evaluate performance using:

   * Accuracy
   * Confusion Matrix
   * Classification Report
7. Visualize results with heatmap

---

## ▶️ Usage

1. Clone the repository:

```id="clone"
git clone https://github.com/your-username/naive-bayes-iris-binary-classifier.git
cd naive-bayes-iris-binary-classifier
```

2. Install dependencies:

```id="install"
pip install pandas numpy matplotlib seaborn scikit-learn
```

3. Run the script:

```id="run"
python naive_bayes.py
```

---

## 📊 Example Output

```id="output"
=== RESULTS ===
Accuracy: 1.0

Confusion Matrix:
[[20  0]
 [ 0 10]]
```

A heatmap visualization will also be displayed.

---

## 📌 Key Concepts

* Naive Bayes Algorithm
* Gaussian Distribution
* Binary Classification
* Confusion Matrix
* Data Visualization

---

## 💡 Future Improvements

* Add GUI using Tkinter or Streamlit
* Extend to multi-class classification
* Add cross-validation
* Deploy as a web app

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork and improve the project.

---

## 📜 License

This project is open-source under the MIT License.
