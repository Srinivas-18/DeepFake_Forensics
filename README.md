# DeepFake_Forensics
This project leverages deep learning to detect deepfake images and explain predictions using Grad-CAM heatmaps. It uses MTCNN for face detection, InceptionResnetV1 for classification, and Gradio to create a simple web-based interface for inference.

### 🔍 Features:
- Face detection and preprocessing
- Deepfake classification (Real/Fake) with confidence scores
- Grad-CAM visualizations to interpret model focus
- Gradio UI for interactive predictions

### 🧰 Technologies Used
- Python, PyTorch, Torchvision
- MTCNN, InceptionResnetV1 (VGGFace2)
- Grad-CAM (pytorch-grad-cam)
- Gradio, OpenCV, NumPy, PIL
