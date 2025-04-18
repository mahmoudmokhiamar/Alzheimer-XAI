# Alzheimer-XAI: Explainable AI for Dementia Stage Classification

This project focuses on applying Explainable AI (XAI) techniques to classify dementia stages from brain MRI scans. It integrates deep learning models and Grad-CAM visualizations to enhance model interpretability, aiding researchers and clinicians in understanding model predictions.

## Objectives

- Classify dementia stages using a CNN model.
- Apply Grad-CAM to identify important brain regions influencing predictions.
- Demonstrate model performance using evaluation metrics like F1 Score.
- Provide visual insights to support explainability in medical AI applications.

## Features

- High accuracy with 92% F1 score in multiclass classification.
- Grad-CAM heatmaps to visualize model attention.
- Focus on medical interpretability for better decision support.

## Tools & Technologies

- Python (NumPy, Matplotlib, Seaborn)
- TensorFlow / Keras
- Grad-CAM for Explainable AI
- Jupyter Notebook for interactive experimentation

## Folder Structure

```
Alzheimer-XAI/
│
├── Alzheimer-XAI.ipynb        # Main notebook
├── README.md                  # Project documentation
└── /images/                   # Output Grad-CAM visualizations
```

## Results

- Trained a custom CNN on dementia MRI datasets.
- Achieved a 92% F1 Score.
- Generated Grad-CAM maps highlighting influential brain regions per class.

## Explainability Example

Using Grad-CAM, the network highlights the hippocampus and surrounding cortical areas in images classified as "Mild Dementia", aligning with clinical expectations.

## How to Run

1. Clone the repo and install dependencies.
2. Open the `Alzheimer-XAI.ipynb` in Jupyter.
3. Run the cells to train the model and view the Grad-CAM results.

## Use Cases

- Clinical decision support for neurologists.
- Educational tool for understanding CNN behavior in healthcare.
- Research foundation for interpretable medical imaging models.

## License

This project is released under the MIT License.
