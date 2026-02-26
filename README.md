# Brain Tumor MRI Classifier with Explainable AI

## Overview

This project implements a deep learning pipeline for brain tumor classification from MRI images using transfer learning and Grad-CAM for visual explainability.

The system includes:

- A multi-class MRI classifier (glioma, meningioma, pituitary tumor, no tumor)
- Grad-CAM visual explanations to highlight model attention
- A rule-based explanation agent that generates text grounded in model evidence
- An interactive Streamlit web interface for image upload and analysis
