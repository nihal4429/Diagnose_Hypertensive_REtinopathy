🧠 Hypertensive Retinopathy Detection using EfficientNetB0
A deep learning-based diagnostic system that automatically classifies and grades Hypertensive Retinopathy (HR) from fundus images using the EfficientNetB0 model. This system enhances the accuracy, speed, and accessibility of retinal screening — especially in resource-constrained or remote settings.

📌 Project Summary
Hypertensive Retinopathy (HR) is a vision-threatening condition caused by prolonged high blood pressure. Early and accurate diagnosis is essential but often limited by the availability of trained ophthalmologists. This project uses EfficientNetB0 to automatically classify retinal fundus images into one of four HR grades (0 to 3) — enabling early intervention.

🏁 Objectives
Automate detection and grading of HR from retinal images.

Replace manual screening with an accurate, scalable AI model.

Empower clinicians in low-resource regions with decision support tools.


🧠 Technologies Used
Technology	Description
EfficientNetB0	CNN backbone for HR image classification
Python + TensorFlow	Model training, inference & visualization
Jupyter/Colab	Model development and evaluation environment
CSV Reporting	Batch result export for clinics

🏥 Target Audience
Primary: Ophthalmologists, general practitioners, rural health workers.

Secondary: Medical AI researchers, health informatics developers, telemedicine providers.

🔍 Features
✅ Core Features
Upload and preprocess fundus images.

Predict HR grade (0 to 3).

Display Grad-CAM heatmaps for model explainability.

Export results to CSV.

Batch processing of images.

🔐 Additional Features
Role-based access for medical staff, researchers, and admin.

Fully functional in backend-only (no frontend/UI dependency).

Tested for up to 95.61% model accuracy.

📊 Model Pipeline
text
Copy
Edit
Fundus Image Input
     ↓
Preprocessing (resize, normalize)
     ↓
EfficientNetB0 Model (Transfer Learning)
     ↓
Prediction (Grade 0–3)
     ↓
CSV Report Generation
📦 Product Modules
Module	Description
Image Upload	Accepts high-res fundus images
Model Inference Engine	EfficientNetB0 architecture with fine-tuning
Visual Explainability	Grad-CAM heatmaps highlight decision regions
Report Generation	CSV-based output of predictions
Admin Panel (Prototype)	Monitor usage and feedback collection

🧪 Evaluation Metrics
Accuracy: 95.61%

Confusion Matrix: Assesses prediction reliability per grade.

Precision & Recall: For model robustness and diagnostic utility.

🚀 Future Enhancements
⚙️ Mobile app integration for field screenings.

🧩 Support for other eye diseases (DR, Glaucoma).

🌐 Real-time cloud deployment with EHR integration.

🧠 Vision Transformers (ViTs) and advanced explainability (attention maps).

🔁 Feedback-based continual learning loop.

🌍 SDG Alignment
This project directly supports:

SDG 3 – Good Health & Well-being

SDG 9 – Industry, Innovation & Infrastructure

📚 Academic & Clinical Value
Research prototype validated via multiple sprints.

Implemented using best practices (MoSCoW, user stories, sprint planning).

Tested in lab settings, optimized for clinical deployment.

👨‍💻 Authors
Nihal Singh
