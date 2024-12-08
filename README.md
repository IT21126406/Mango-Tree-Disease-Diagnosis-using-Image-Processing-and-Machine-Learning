# Mango Tree Disease Diagnosis using Image Processing and Machine Learning

## Project Overview

This project aims to develop an automated system for accurately detecting and classifying diseases in mango trees using image processing techniques and machine learning algorithms. The target audience for this system is home gardeners in Sri Lanka who often struggle with low crop yields due to a lack of knowledge about proper maintenance and disease management.

## Table of Contents

- [Project Overview](#project-overview)
- [Table of Contents](#table-of-contents)
- [Problem Statement](#problem-statement)
- [Solution](#solution)
- [Specialized Domain Expertise](#specialized-domain-expertise)
- [Objectives and Novelty](#objectives-and-novelty)
- [Team Members](#team-members)
- [Supervisor Checklist](#supervisor-checklist)
- [Supervisor Details](#supervisor-details)
- [Review Panel Details](#review-panel-details)
- [Getting Started](#getting-started)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Problem Statement

Many gardens in Sri Lanka have mango trees, but gardeners often face challenges such as diseases (e.g., anthracnose, powdery mildew, bacterial canker) and pests (e.g., fruit flies, mango hoppers). These issues lead to low crop yields, stunted tree growth, and even tree death. The lack of knowledge about pest and disease management often results in ineffective treatments. Additionally, uncontrolled tree growth and insufficient nutrition adversely affect tree and crop growth.

## Solution

The proposed solution involves creating an automated system to detect and classify mango tree diseases using image processing and machine learning. The system will:

1. **Data Acquisition**: Collect a comprehensive dataset of mango fruit, leaves, and plant images, both healthy and diseased, under varying conditions.
2. **Preprocessing**: Enhance image quality through techniques such as color space transformation, noise reduction, and normalization.
3. **Segmentation**: Apply image segmentation methods to isolate items from the background and focus on regions of interest.
4. **Feature Extraction**: Use texture analysis, color histograms, and shape descriptors to extract relevant features.
5. **Model Training**: Train machine learning models, particularly Convolutional Neural Networks (CNNs), using the extracted features.
6. **Evaluation**: Validate the model's accuracy and robustness using a separate set of test images.
7. **Deployment**: Implement the trained model in a user-friendly application for real-time disease diagnosis.

## Specialized Domain Expertise

The successful implementation of this project requires expertise in:

- *Agricultural Science and Plant Pathology*
- *Artificial Intelligence and Machine Learning*
- *Software Development and UX Design*
- *Data Science and Analytics*

## Objectives and Novelty

- **Main Objective**: Develop an application for diagnosing diseases in mango trees and providing the best solutions using image processing and machine learning algorithms.
- **Novelty**: The system aims to raise awareness about natural remedies, offer new gardening tips and techniques, and promote Good Agricultural Practices (GAP) to home gardeners.

## Contributors

A big thank you to everyone who has contributed to this project.

- **Himeth Thewnuka**(https://github.com/contributor1)
- **Dushan Hemathunga**(https://github.com/contributor2)
- [**Sahan Ramanayake**](https://github.com/IT21126406)
- **Navodya Weerasinghe**(https://github.com/contributor4)

## Supervisor Checklist

- **Comprehensive Scope**: Yes
- **Novelty**: Yes
- **Capability to Execute**: Yes
- **Sub-Objectives Reflect Specialization**: Yes

## Supervisor Details

- **Supervisor**: Prof. Pradeep Abeygunawardhana
- **Co-Supervisor**: Ms. Manori Gamage

## Getting Started

To get started with this project, follow these steps:

1. **Clone the Repository**:  
   ```bash
   git clone https://github.com/IT21126406/Mango-Tree-Disease-Diagnosis-using-Image-Processing-and-Machine-Learning.git
   cd mango-disease-diagnosis
   ```

2. **Install Dependencies**:  
   Ensure you have Python 3.8+ installed. Then, run:  
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Notebooks**:  
   Open the following notebooks sequentially in Jupyter Notebook or Google Colab:  
   - `Mango_Fruit_Diseases_mobileNetV2_classification.ipynb`: For mango fruit disease detection.  
   - `Mango_Leaf_Diseases_MobileNet.ipynb`: For mango leaf disease detection.  
   - `Mango_Tree_Stages_inception_v3.ipynb`: For classifying the growth stages of mango trees.  
   - `chatbot.ipynb`: For the AI-powered chatbot that assists with disease prevention, treatment recommendations, and general guidance.

4. **Test the System**:  
   - Upload test images of mango fruits, leaves, or trees to the respective notebooks.  
   - Use the chatbot to simulate interactions and obtain tailored farming advice.  

5. **Run the Application**:  
   If a complete integration is provided:  
   ```bash
   python main.py
   ```

## Technologies Used

- **Programming Languages**: Python  
- **Libraries and Frameworks**: TensorFlow, Keras, OpenCV, NumPy, Pandas, Flask (for chatbot and application integration)  
- **Tools**: Jupyter Notebook, Google Colab  
- **Machine Learning Models**: MobileNetV2, InceptionV3  
- **Deployment**: Flask or equivalent lightweight server for integration  

## Contributing

We welcome contributions from the community. To contribute:

1. Fork the repository.  
2. Create a new branch (`git checkout -b feature-branch`).  
3. Make your changes and commit them (`git commit -m 'Add some feature'`).  
4. Push to the branch (`git push origin feature-branch`).  
5. Open a pull request.  

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
