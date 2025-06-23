# 🖼️ Image Handling and Affine Transformation using Python

This project showcases basic to advanced image processing techniques using Python, with a focus on **Affine Transformations** such as rotation, scaling, translation, shearing, and perspective changes.

---

## 🔧 Tools & Libraries Used

- **Python 3.x**
- **OpenCV** (`cv2`)
- **NumPy**

---

## 📌 Features

- Load and display images
- Perform **Affine Transformations**:
  - Translation
  - Rotation
  - Scaling
  - Shearing
- Save processed images to output folder


---

##  What is Affine Transformation?

Affine Transformation is a linear mapping method that preserves points, straight lines, and planes. Common operations include:

| Operation   | Description                                   |
|-------------|-----------------------------------------------|
| Translation | Moves the image along X and/or Y direction    |
| Rotation    | Rotates the image by a certain angle          |
| Scaling     | Enlarges or shrinks the image                 |
| Shearing    | Tilts the image along X or Y axis             |

These are done using **transformation matrices** and `cv2.warpAffine()` function in OpenCV.



