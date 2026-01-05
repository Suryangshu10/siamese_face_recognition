# siamese_face_recognition
Repo for WiDS  project

🧠 Siamese Network for Face Verification

Midterm Project Submission (Progress Report)

📌 Project Overview

This project focuses on understanding and partially implementing a Siamese Neural Network for face verification. The primary objective of the midterm phase is to build conceptual clarity around similarity-based learning and to implement the core building blocks of the Siamese pipeline.

At this stage, the project emphasizes learning, guided implementation, and verification of concepts, rather than a fully developed end-to-end system.

🎯 Scope of Work (Midterm Phase)

The following objectives have been addressed during the midterm period:

Studied the fundamentals of supervised learning

Understood regression models and optimization using gradient descent

Learned the principles of metric learning and Siamese networks

Implemented key components of a Siamese network through guided coding

Verified understanding using small test cases and visualizations

📚 Learning Resources Studied

The following resources were thoroughly studied to build theoretical understanding:

Course-provided document covering:

Supervised vs. unsupervised learning

Linear and multiple regression

Cost functions and gradient descent

Feature scaling and feature engineering

Recommended video lectures on Siamese Networks and metric learning

Supplementary examples and conceptual walkthroughs

At this stage, these resources have been studied and understood, but not yet fully implemented independently in code.

🧪 Coding Work Completed So Far

The following guided coding tasks have been completed to validate understanding:

1. Data Handling

Creation and filtering of datasets using Pandas

Basic data inspection and selection logic

2. Image Preprocessing

Reading images using OpenCV

Converting images to grayscale

Resizing images to 105 × 105 pixels

Normalizing pixel values to the range [0, 1]

3. Siamese Network Building Block

Implementation of a single Siamese tower consisting of:

Convolutional layer (64 filters, 10 × 10 kernel)

Max pooling layer (2 × 2)

Flatten layer

Fully connected embedding layer (4096 units)

This code was implemented to understand network structure and data flow, not as a complete training pipeline.

🧠 Similarity Decision Logic

A simple threshold-based classification logic was implemented:

If similarity score > 0.5 → Same person

Else → Different person

This helped reinforce the concept of distance-based decision making in Siamese networks.

📊 Current Project Status

✅ Core preprocessing steps understood and implemented

✅ Siamese tower architecture understood and coded

✅ Similarity-based decision logic tested

📖 Full training loop, loss computation, and evaluation studied but not yet coded

🛠️ Tools & Technologies

Python

TensorFlow / Keras

OpenCV

NumPy

Pandas

Matplotlib

🧩 Key Learnings So Far

Difference between classification and verification problems

Importance of shared weights in Siamese networks

Role of embeddings in similarity learning

Why contrastive loss is preferred over standard classification loss

How preprocessing choices affect network performance

🔮 Planned Work (Post-Midterm)

The following components are planned for implementation in the next phase:

Complete Siamese network with dual inputs

Contrastive loss implementation

Training loop and validation

Performance evaluation and threshold tuning

Dataset scaling and robustness testing

📌 Conclusion

This midterm submission represents a conceptually complete understanding of Siamese networks and their application to face verification. While only guided core components have been implemented so far, the theoretical foundation and architectural understanding required for full implementation have been established.

The project is well-positioned for completion in the subsequent phase with independent coding and experimentation.
