# defect-detector
Pill Defect Detection using Machine Learning
This project uses deep learning and image processing to classify pills as Normal or Defective, aiding in quality control for pharmaceutical manufacturing. The model identifies issues such as cracks, chips, or surface defects using a dataset of labeled pill images.


📌 Project Overview
The goal is to create a reliable and efficient defect detection system by training a machine learning model to analyze pill images. Normal pills are marked with a green circle, and defective pills with a red circle, as shown above.

🔍 Features
✅ Image classification: Normal vs Defective pills

🧠 Deep learning model using TensorFlow

🖼️ Image preprocessing with OpenCV

🎯 Visualization of classification with bounding circles

🧪 CLI or GUI interface to test new pill images

📈 Accuracy reporting and performance metrics

📂 Dataset
The project uses the Pill-Defects dataset available on GitHub:

🔗 https://github.com/PerceptiLabs/Pill-Defects

It contains:

Defect/ – Images of pills with visible defects

Normal/ – Images of defect-free pills

Additional images may be added manually for further enhancement.

🛠 Tools & Libraries
Python 3.x

TensorFlow – Model training and prediction

OpenCV – Image processing and visualization

Scikit-learn – Model evaluation

NumPy, Pandas – Data handling

Matplotlib, Seaborn – Visualization

Jupyter / VS Code – Development environments

🧪 Current Development
✅ Model trained to classify pill images

⚙️ Working on overlaying:

🔴 Red circles for defective pills

🟢 Green circles for normal pills (see reference image)

🛠 GUI/CLI interface is in progress

📅 Timeline
Week	Task
1	Dataset research and scope definition
1	Image collection and preprocessing
2	Model training and validation
3	Model optimization
3-4	Image processing pipeline
5	GUI/CLI implementation
6	Testing and final documentation

📄 License
This project is for educational purposes. Dataset is publicly available via GitHub. All credits to the original dataset authors.
