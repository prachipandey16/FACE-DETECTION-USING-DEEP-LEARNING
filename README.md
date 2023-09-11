# FACE-DETECTION-USING-DEEP-LEARNING

Introduction:

About Facial Detection
A computer vision activity called facial detection looks for and recognizes faces in pictures and movies. To locate the position and borders of faces in a given visual input, it entails utilizing algorithms and models, frequently based on deep learning. Numerous applications, including security systems, photography, emotion analysis, and, more recently, augmented reality filters and facial recognition systems, all use this technology as a fundamental building block.

About MTCNN:
MTCNN (Multi-task Cascaded Convolutional Networks) revolutionized facial detection by employing a cascading architecture of deep neural networks. It adeptly detects faces in images of varying sizes, while estimating landmarks and attributes. Its cascading stages—Proposal, Refinement, and Output Networks—combine for accurate and efficient facial detection, aiding diverse applications.
Methodology
MTCNN (Multi-task Cascaded Convolutional Networks) employs a multi-stage methodology for facial detection:

Proposal Network (P-Net): This initial stage generates potential face candidate boxes through convolutional layers and applies a bounding box regression to refine their positions. It also predicts the probability of each candidate containing a face.

Refinement Network (R-Net): The R-Net filters out false positives from P-Net's candidates, improving accuracy. It refines the bounding box positions and performs facial landmark localization, which helps align the detected faces accurately.

Output Network (O-Net): The final stage enhances accuracy by further filtering out false positives and refining bounding boxes and landmarks. Additionally, it predicts attributes like gender and age.

The cascading structure of MTCNN improves detection progressively. It starts with a rapid but coarse detection (P-Net), refines candidates (R-Net), and eventually delivers precise face detection and landmarks (O-Net). This multi-task approach has made MTCNN a robust choice for accurate and efficient facial detection in various applications.

# RESULTS
![Screenshot 2023-07-19 211243](https://github.com/prachipandey16/FACE-DETECTION-USING-DEEP-LEARNING/assets/115707069/7071d4dc-0b40-4f23-a527-0486dcd4da79)

