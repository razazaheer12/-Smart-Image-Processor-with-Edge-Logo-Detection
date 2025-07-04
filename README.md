# -Smart-Image-Processor-with-Edge-Logo-Detection

A smart image processing tool built in Google Colab using OpenCV.   Performs edge detection, document classification, and optional logo detection from uploaded images.

📸 Features

✅ Upload image directly in Colab (no path input needed)  
🧠 Automatically performs:  
- Edge detection (Canny, Sobel, Laplacian)  
- Logo detection using template matching (optional)  
- Document type classification (portrait vs landscape)  
💾 Saves all output images in an `outputs/` folder  
📊 Displays results in Colab using `cv2_imshow`

🚀 How to Use

1. Open the notebook in Google Colab.
2. Run all cells step by step.
3. Upload a face or document image when prompted.
4. Optionally provide a logo template path for matching.
5. View and download processed results.

🛠️ Technologies Used

- Python 3  
- OpenCV (cv2)  
- NumPy  
- Google Colab tools (`cv2_imshow`, `files.upload`)  
- Matplotlib (for initial image preview)


