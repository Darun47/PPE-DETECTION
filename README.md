# Project overview
This project is an computer vision-based PPE(personal protective equipments) Detection system which uses machine learning and deep learning concepts. 
This system automatically identifies wether a construction site worker is wearing the equipments properly such as helmets, safety vests, and masks.
If there is an missing equipment then this model will detect and provide the unequiped item.
It is built using the yolov8 which detects the real time object and deployed through a steamlit dashboard, offering an interactive and user-friendly interface to display compliance levels in real time.

Project Aims

Develop an AI model to detect PPE items including hardhats, masks, and safety vests.
Classify workers based on compliance levels:
Green Compliant: All PPE items detected
Yellow Partially Compliant: One or two PPE items detected
Red Non-Compliant: No PPE detected
Deploy the system on Streamlit Cloud for live monitoring and inference.

Model Specifications

Model Used: YOLOv8
Reason for Selection: High detection accuracy, fast inference speed, and seamless Python integration.
Classes Trained:
Hardhat
Mask
Safety Vest
No-Hardhat
No-Mask
No-Safety Vest

Process workflow

Dataset Preparation
PPE images of construction workers were collected and labeled.
Data split: 70% Training, 30% Testing.
Model Training
On Google Colab, the YOLOv8 model was trained with pre-trained weights.
Model Evaluation
tested on unseen images to evaluate the consistency and accuracy of detection.
Implementation
For real-time monitoring and visualization, an interactive Streamlit dashboard was put into place on Streamlit Cloud.

Results and Observations

The model consistently achieved accurate detections even in complex or cluttered environments.
It successfully differentiated between workers wearing full, partial, or no protective equipment, offering a reliable automation method for safety audits.

Conclusion

The PPE Detection and Compliance Monitoring System demonstrates the power of AI-driven computer vision in improving workplace safety.
By combining YOLOv8’s detection capabilities with Streamlit’s interactive interface, the project offers a complete, automated solution for real-time PPE compliance tracking.
From data collection and model training to deployment and visualization, the project encapsulates the entire AI workflow while addressing a meaningful real-world problem — ensuring safer, smarter, and more efficient construction sites.


