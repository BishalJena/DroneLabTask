### **Task 2: Train a Brain Tumor Detection Model**

#### **Task Overview**

Participants are required to **fine-tune a YOLO object detection model** for brain tumor detection using MRI images. Fine-tuning involves modifying an existing weights to adapt it for detecting brain tumors from medical images.

The assignment introduces you to key machine learning concepts such as transfer learning, model fine-tuning, and evaluating model performance in the context of medical image classification You’re free to choose any version of YOLO for your model. However, be sure to document your selection and explain the key factors that influenced your decision
#### **Task Objectives**

1. **Preprocess the Dataset**: Prepare the dataset of MRI images for the model
	*Tip: Leverage a pre-existing dataset to jumpstart your work*
2. **Fine-tune a Pre-trained Model**: Use transfer learning to adapt a pre-trained model for binary classification (tumor/no-tumor).
3. **Model Training**: Train the model on the dataset, adjusting hyperparameters to achieve the best performance.
4. **Evaluate the Model**: Measure the performance of the model using relevant metrics (accuracy, precision, recall, F1-score) and do mention them in doc.
5. **Submit Deliverables**: Submit a github repo link containing model, code and the documentation.
#### **Task Deliverables**

1. **Fine-tuned Model and Code:**
	* Python code for preprocessing, model fine-tuning, and evaluation.
	* The trained model (saved in .h5 or .pt format, depending on the framework used).

2. **Documentation:** A report in PDF format that includes:
	* Preprocessing steps: What steps were taken to prepare the data (resizing, normalization, augmentation).
	* Model architecture: Which pre-trained model was used and how it was modified.
	* Training process: Description of hyperparameters (batch size, learning rate, number of epochs).
	* Evaluation metrics: Accuracy, precision, recall, F1-score, and other observations from the results.
	* Instructions: How to run the code and reproduce the results.

3. **Demo Video:** A short video (3-5 minutes) recorded using [loom](https://www.loom.com/)
	* The code running in action.
	* A brief explanation of the approach.
	* Model performance on a few test case

**NOTE:** Partial submissions are welcome! Even if your project isn't fully complete, we encourage you to submit your work. Demonstrating your approach, progress, and problem-solving process is just as important as achieving a final solution.

---
### **Resources for Participants**

Participants will be expected to understand basic machine learning concepts and learn how to apply transfer learning and model fine-tuning using existing frameworks like TensorFlow or PyTorch. To help you hit the ground running, we’ve curated a list of essential resources below:
1. [https://docs.ultralytics.com](https://docs.ultralytics.com/modes/train/)
2. [https://www.comet.com/site](https://www.comet.com/site/blog/fine-tuning-yolov8-for-image-segmentation-with-comet/)
3. [https://www.datature.io/blog](https://www.datature.io/blog/yolov9-a-comprehensive-guide-and-custom-dataset-fine-tuning)
---
### **Evaluation Criteria**
- Model Fine-tuning and Training (40 points)
- Documentation (30 points)
- Demo Video (30 points)
---
Good luck with the assignment! If you need any help along the way, feel free to reach out—we're here to guide you, but remember, the project is yours to complete. We're excited to see what you create!
