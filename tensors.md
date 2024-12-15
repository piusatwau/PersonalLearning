# Tensor
- Is a numerical representation of data
- This data can be anything from text to images, audio to video

Tensors are the fundamental building blocks of deep learning 

## Different types of tensors
---

### **1. By Rank (Dimensionality)**
- **Scalar (Rank-0 Tensor):**
  - A single number (e.g., \(5, -3, \pi\)).
  - Represented as a tensor with no dimensions.

- **Vector (Rank-1 Tensor):**
  - A one-dimensional array of numbers (e.g., \([3, 7, -1]\)).
  - Represents magnitude and direction.

- **Matrix (Rank-2 Tensor):**
  - A two-dimensional array of numbers (e.g., a grid of values).
  - Commonly used in linear algebra.

- **Higher-Order Tensors (Rank-3 and above):**
  - Multi-dimensional arrays.
    - **Rank-3 Tensor:** A cube-like data structure (e.g., RGB images).
    - **Rank-n Tensor:** n-dimensional generalization (e.g., data from sensors in machine learning).

---

### **2. Based on Symmetry**
- **Symmetric Tensor:**
  - Unchanged under permutations of indices.
  - Example: A 2nd-order symmetric tensor \(\mathbf{A}\) satisfies \(A_{ij} = A_{ji}\).

- **Asymmetric/Skew-Symmetric Tensor:**
  - Negates under the exchange of two indices.
  - Example: For \(A_{ij}\), \(A_{ij} = -A_{ji}\).

- **Anti-Symmetric Tensor:**
  - A type of skew-symmetric tensor where elements vanish if two indices are equal.

---

### **3. Based on Field of Application**
- **Physics Tensors:**
  - **Stress Tensor:** Describes forces within a material (\( \sigma_{ij} \)).
  - **Strain Tensor:** Describes deformation (\( \varepsilon_{ij} \)).
  - **Inertia Tensor:** Represents rotational properties of a body.

- **Machine Learning Tensors:**
  - Data structures in frameworks like TensorFlow and PyTorch.
  - Tensors store data for neural networks (e.g., inputs, weights, and activations).

- **General Relativity Tensors:**
  - **Metric Tensor (\(g_{\mu\nu}\)):** Defines spacetime geometry.
  - **Riemann Tensor:** Encodes information about spacetime curvature.

---

### **4. Sparse vs Dense Tensors**
- **Sparse Tensor:**
  - Contains mostly zeros.
  - Efficiently stored by only recording non-zero elements and their indices.

- **Dense Tensor:**
  - Contains mostly non-zero elements.
  - Stored as a standard multi-dimensional array.

---

### **5. Euclidean vs Non-Euclidean Tensors**
- **Euclidean Tensor:**
  - Defined in flat (Euclidean) space.
  - Operations like dot and cross products are valid.

- **Non-Euclidean Tensor:**
  - Defined on curved surfaces or manifolds.
  - Operations are adapted to the geometry of the space.

---

### **6. Transformation Properties**
- **Contravariant Tensor (\(T^i\)):**
  - Transform in one direction under a coordinate change.

- **Covariant Tensor (\(T_i\)):**
  - Transform in the opposite direction under a coordinate change.

- **Mixed Tensor (\(T_i^j\)):**
  - Contain both covariant and contravariant components.

---

### **7. By Special Properties**
- **Identity Tensor:**
  - The generalization of the identity matrix.

- **Rank-One Tensor:**
  - Outer product of vectors.

- **Tensor Field:**
  - A tensor that varies across space or time (e.g., vector fields in fluid dynamics).

---

If you're working in a specific field, let me know, and I can focus more on tensors relevant to that domain!
