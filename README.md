# 🚗 Image Segmentation with U-Net (Self-Driving Car Dataset)

Welcome to the **Image Segmentation with U-Net** project! This repository demonstrates how to build a U-Net model for image segmentation using a self-driving car dataset. 🚀

---

## 🌟 Key Features

- Implementation of the U-Net architecture for semantic segmentation.
- Preprocessing pipelines for images and masks. 🖼️
- Step-by-step demonstration of encoding and decoding paths for U-Net.
- Insights into TensorFlow and Keras functionalities for deep learning tasks. 🤖

---

## 📂 Project Structure

1. **Data Loading & Splitting**  
   - Load the RGB images and corresponding segmentation masks.  
   - Split data into image and mask pairs.  

2. **Data Preprocessing**  
   - Resizing and normalizing the images and masks.  
   - Mapping preprocessing pipelines with TensorFlow datasets.  

3. **U-Net Architecture**  
   - Contracting path: Downsampling using convolutional layers.  
   - Expanding path: Upsampling and concatenation for detailed segmentation.  
   - Skip connections: Retain essential spatial details for reconstruction.

4. **Visualization**  
   - Display sample images and segmentation masks. 🎨

---

## 🛠️ Installation & Setup

1. Clone the repository:  
   ```bash
   git clone https://github.com/MohammedSaqibMS/Image_Segmentation_Unet.git
   cd Image_Segmentation_Unet
   ```

2. Install required dependencies:  
   ```bash
   pip install -r requirements.txt
   ```

3. Download the dataset and place it in the `data` directory:  
   - Images: `data/CameraRGB/`  
   - Masks: `data/CameraMask/`

4. Run the notebook or script to train the model and visualize results.

---

## 🚀 Technologies Used

- **Frameworks**: TensorFlow, Keras  
- **Libraries**: NumPy, Pandas, Matplotlib, ImageIO  
- **Tools**: Jupyter Notebook

---

## 🎯 Results

- High-quality segmentation outputs using the U-Net architecture.  
- Efficient preprocessing and visualization of datasets.  
- Scalable approach for semantic segmentation tasks in self-driving car systems.

---

## 🙌 Acknowledgments

This project is inspired by the **Deep Learning Specialization** from [deeplearning.ai](https://www.deeplearning.ai/courses/deep-learning-specialization/). Special thanks for their exceptional content on deep learning and U-Net architecture! 💡

---

## 📜 License

This repository is licensed under the MIT License. See the `LICENSE` file for details.  

---

## 🌐 Connect

- Author: [Muhammad Saqib](https://github.com/MohammedSaqibMS)  
- Questions or suggestions? Feel free to open an issue!  

Happy coding! 🎉
