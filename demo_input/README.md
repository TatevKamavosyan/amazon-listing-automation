# Amazon Listing Image Automation

This project automates the process of preparing high-quality product images for Amazon listings. It uses AI-powered background removal and standardized resizing to ensure all images meet professional e-commerce requirements.

## 🚀 Key Features
* **AI Background Removal**: Utilizes the `rembg` library for precise object isolation.
* **Automated Resizing**: Standardizes all output images to a 1000x1000 square format with a clean white background.
* **Batch Processing**: Capable of processing multiple images simultaneously from the `demo_input` folder.

## 🛠 Tech Stack
* **Python**: Core logic and automation.
* **rembg (U2Net)**: Deep learning model for background subtraction.
* **Pillow (PIL)**: Image manipulation and canvas padding.
* **Google Colab**: Environment for seamless cloud execution.

## 📂 Project Structure
* `450photos.ipynb`: The main automation script.
* `demo_input/`: Folder containing sample product images for testing.

## 📖 How to Use
1. Open the `.ipynb` file in Google Colab.
2. Run the setup cell to install dependencies (`rembg`, `pillow`).
3. Upload your raw images or use the ones provided in `demo_input`.
4. The processed images will be saved in the `demo_output` directory, ready for Amazon listing.
