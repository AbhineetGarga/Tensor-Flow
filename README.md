# Tensor Operations with TensorFlow

## 📌 Project Overview
This project demonstrates the **basics of tensor operations using TensorFlow**.  
The notebook explores how tensors work, how to create them, and how to perform different mathematical operations using TensorFlow.

The goal of this project is to understand the **core building blocks of deep learning frameworks**, since tensors are the fundamental data structures used in **machine learning and neural networks**.

---

# 📂 Project File

```
tensor.ipynb
```

The notebook contains examples and explanations of **TensorFlow tensor operations and manipulations**.

---

# ⚙️ Technologies Used

- **Python**
- **TensorFlow**
- **NumPy**
- **Jupyter Notebook**

---

# 🧠 Concepts Covered

This project covers the following TensorFlow concepts:

### 1️⃣ Creating Tensors
Different ways to create tensors using TensorFlow.

Examples include:
- Constant tensors
- Zero tensors
- One tensors
- Random tensors

```python
import tensorflow as tf

tensor = tf.constant([[1, 2], [3, 4]])
```

---

### 2️⃣ Tensor Shapes and Dimensions
Understanding tensor shapes and ranks.

```python
tensor.shape
tf.rank(tensor)
```

---

### 3️⃣ Tensor Operations
Basic mathematical operations performed on tensors.

Examples:
- Addition
- Multiplication
- Matrix multiplication

```python
tf.add(a, b)
tf.multiply(a, b)
tf.matmul(a, b)
```

---

### 4️⃣ Tensor Manipulation
Operations used to reshape and modify tensors.

Examples include:
- Reshaping tensors
- Expanding dimensions
- Squeezing dimensions

```python
tf.reshape(tensor, (4,1))
```

---

### 5️⃣ Tensor Conversion
Conversion between **NumPy arrays and TensorFlow tensors**.

```python
import numpy as np

array = np.array([1,2,3])
tensor = tf.convert_to_tensor(array)
```

---

# 🚀 How to Run the Project

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/your-repository-name.git
```

### 2️⃣ Install required libraries

```bash
pip install tensorflow numpy jupyter
```

### 3️⃣ Run the notebook

```bash
jupyter notebook
```

Open:

```
tensor.ipynb
```

---

# 📈 Learning Outcomes

After completing this project, you will understand:

- What tensors are
- How TensorFlow represents data
- Basic tensor operations
- Tensor reshaping and manipulation
- Converting between NumPy arrays and tensors

These concepts are fundamental for building **deep learning models using TensorFlow and Keras**.

---

# 🔮 Future Improvements

Possible extensions for this project:

- TensorFlow computational graphs
- GPU acceleration
- TensorFlow with neural networks
- Building a simple deep learning model

---

# 👨‍💻 Author

Machine learning practice project created to explore **TensorFlow tensor operations and deep learning fundamentals**.
