# Advance-Virtual-TryON

Overview
This project presents an innovative 2D Virtual Try-On System that provides a seamless and immersive try-on experience using HR-VITON, a high-resolution virtual try-on model. It addresses limitations in traditional try-on methods by enabling users to visualize garments on themselves in real time, ensuring personalized and engaging shopping experiences.

Problem Statement
Traditional try-on solutions are either too simplistic (using dummy models) or overly complex (3D-based systems), making them ineffective for personalized use. This project aims to develop a robust, 2D-based virtual try-on system that generates high-resolution, realistic results.

Proposed Solution
Advanced Segmentation

Developed custom binary masks to accurately segment garments, accounting for diverse textures and lighting conditions.
Optimized dense pose mapping to manage complex user poses effectively.
Pose Estimation

Used PoseNet for robust alignment and precise keypoint extraction, ensuring realistic garment overlay.
2D Virtual Try-On

Integrated HR-VITON, a deep learning model, to generate high-resolution try-on results using user and garment images.
Modular Design

Designed reusable modules for efficient integration and scalability.
Code Implementation

Created scripts for:
Garment masking
Dense pose mapping
Grayscale segmentation
Pose estimation
A main driver script orchestrates all modules for seamless try-on outputs.
Why HR-VITON?
High-Resolution Outputs: Generates realistic 1024x768 virtual try-on images.
Efficient 2D Approach: Simplifies computation while maintaining accuracy.
Robust Handling: Seamlessly addresses garment misalignment and occlusions.
Pre-Trained on VITON-HD: Adaptable to diverse clothing and user scenarios.
Easy Integration: PyTorch-based implementation ensures smooth pipeline adaptation.
Results
Achieved accurate garment segmentation and dense pose mapping for precise alignment.
Extracted robust keypoints using PoseNet for realistic garment placement.
Produced high-resolution (1024x768) try-on outputs with seamless integration of modular scripts.
Developed a scalable framework with potential for future enhancements.
Future Enhancements
Real-Time AR Integration: Implement dynamic, real-time augmented reality for interactive garment fitting.
Dataset Expansion: Incorporate diverse garments, user demographics, and styles to improve model generalization.
Hybrid 2D-3D Modeling: Combine 2D and 3D techniques for a more immersive experience.
Multi-Garment Support: Allow users to try combinations of clothing items, such as tops and bottoms.
Technologies Used
HR-VITON: High-resolution virtual try-on with misalignment and occlusion handling.
PoseNet: Human pose estimation and keypoint extraction.
Graphonomy: Semantic segmentation for body part understanding.
Detectron2: Dense pose estimation and segmentation.
Cloth Image Segmentation: Techniques for garment segmentation.
References
HR-VITON Paper: "High-Resolution Virtual Try-On with Misalignment and Occlusion-Handled Conditions" by Sangyun Lee.
PoseNet: Human pose estimation framework.
Graphonomy: Semantic segmentation for body parts.
Detectron2: Dense pose estimation and segmentation framework.
Cloth Image Segmentation: Techniques for accurate garment segmentation.
How to Run the Project
Clone the repository:
bash
Copy code
git clone https://github.com/your-repo-url
Install the required dependencies:
bash
Copy code
pip install -r requirements.txt
Run the main driver script:
bash
Copy code
python main.py
Acknowledgments
This project was conducted under the guidance of Dr. Manish Bhanu. Special thanks to the research community for providing tools and frameworks like HR-VITON, PoseNet, and Detectron2.

Feel free to customize this README further based on the exact repository structure or additional details!






