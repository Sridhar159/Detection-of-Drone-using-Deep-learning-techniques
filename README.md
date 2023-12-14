# Detection-of-Drone-using-Deep-learning-techniques

**Overview**
This project aims to detect drones using computer vision techniques and the Detecto library in Python. The process involves mounting Google Drive, preparing the dataset, training a detection model, and evaluating its performance. The model is capable of real-time detection as demonstrated in the live video detection section.

# Project Structure

**Data Preparation:**
Mounting Google Drive and setting up the working directory.
Converting XML labels to a single CSV file for efficient handling.

**Model Training:**
Installing the Detecto library.
Creating a dataset with optional data augmentation transforms.
Training the detection model using the Faster R-CNN architecture.

**Evaluation:**
Assessing the model's performance on a subset of the validation dataset.
Visualizing the model's predictions on selected images.

**Live Detection:**
Demonstrating the model's real-time detection capabilities on a video file.

**Conclusion**
The implemented drone detection model performs effectively on the provided dataset. Further fine-tuning could enhance its performance. Users can adapt and extend this codebase for their specific drone detection tasks.
