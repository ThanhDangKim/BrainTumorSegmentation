# MRI_BrainTumorSeg_DeepLearning
 Using U-net to segment MRI Brain Tumor

## Introduction
Brain tumors, one of the most dangerous and complex types of cancer, require accurate diagnosis and monitoring through imaging methods such as MRI and CT scans. Image segmentation, especially tumor segmentation, plays a crucial role in determining the size, location, and boundaries of brain tumors, which helps doctors plan treatment and evaluate therapy effectiveness.

## Project Objective and Scope
This project aims to evaluate the effectiveness of the U-Net convolutional neural network architecture in the segmentation and diagnosis of medical images, particularly intracranial tumors from MRI scans. The focus is on applying and optimizing the U-Net model to address the specific challenges of accurate and rapid medical image segmentation.

## Dataset: BraTS2020
The BraTS (Brain Tumor Segmentation) challenge focuses on evaluating advanced methods for brain tumor segmentation using multimodal MRI images. The BraTS2020 dataset consists of pre-surgical MRI scans from various institutions, primarily targeting the segmentation of gliomas, which exhibit diverse morphology, appearance, and histology.

## Libraries Used
The following libraries and tools were used in this project:

- tensorflow
- keras
- numpy
- pandas
- matplotlib
- scikit-image
- nibabel
- OpenCV
- sklearn

## Project Structure
- group4_final.ipynb: The main Jupyter notebook containing the entire process from data loading, preprocessing, model training, to evaluation and visualization.
- README.md: This file, providing an overview of the project.

## Methodology
1. Data Preprocessing: Handling MRI data, including normalization, resizing, and augmentation.
2. Model Architecture: Implementing the U-Net architecture for effective segmentation.
3. Training and Evaluation: Splitting the data into training and validation sets, training the model, and evaluating its performance using metrics like Dice coefficient and IoU.
4. Visualization: Visualizing the segmentation results alongside the original MRI images.

## How to Run
1. Clone the repository.
2. Install the required libraries: pip install -r requirements.txt
3. Open the Jupyter notebook group4_final.ipynb and execute the cells sequentially.

## Results
The results section will include an analysis of the segmentation accuracy, with visualizations of the segmented tumors and performance metrics.

## Future Work
Further work could involve:

- Exploring more advanced architectures or modifications to U-Net for improved segmentation.
- Expanding the dataset or incorporating external data for better generalization.
- Implementing real-time segmentation for clinical use.

## Author
- Đặng Kim Thành
- Bùi Quốc Khang

## Contact us
- Contact me via email: dangkimthanh281003@gmail.com
