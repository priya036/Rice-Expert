# Rice Classification System Using ViT

This project involves building a **Rice Classification System** for a superstore billing system. The system uses machine learning techniques and a Vision Transformer (ViT) model to accurately classify 20 different rice varieties based on images, achieving an impressive accuracy of **94%**.

---

## Table of Contents

1. [Features](#features)  
2. [Technologies Used](#technologies-used)  
3. [ViT Model Workflow](#vit-model-workflow)  
4. [Rice Varieties](#rice-varieties)  
5. [Usage](#usage)  

---

## Features

- **Accurate Classification:** Classifies 20 rice varieties using image inputs with **94% accuracy**.  
- **Transformer-based Feature Extraction:** Utilized ViT (Vision Transformer) for efficient feature extraction.  
- **Scalable Solution:** Designed for integration into superstore billing systems to automate product identification.  
- **Flexible Model Design:** Experimented with multiple classification models to find the optimal solution.  

---

## Technologies Used

- **Machine Learning Frameworks:** Python, TensorFlow/Keras  
- **Transformer Model:** Vision Transformer (ViT)  
- **Libraries:** NumPy, Pandas, Scikit-learn, Matplotlib, Seaborn  

---

## ViT Model Workflow

1. **Preprocessing:** 
   - Resized and normalized rice grain images to ensure consistency.  
2. **Feature Extraction:**
   - Leveraged the Vision Transformer (ViT) to extract meaningful features from images.  
3. **Model Training:**
   - Trained multiple classification models (e.g., SVC, Logistic Regression, Random Forest).  
   - Achieved the best accuracy of **94%** using the final optimized model.  

---

## Rice Varieties

The system classifies the following 20 rice varieties:  
1. Basmati  
2. Jasmine  
3. Arborio  
4. Brown  
5. Wild  
6. Black  
7. Red  
8. Sushi  
9. Glutinous  
10. Long Grain White  
11. Short Grain White  
12. Parboiled  
13. Medium Grain White  
14. Sticky  
15. Organic Brown  
16. Wehani  
17. Carnaroli  
18. Himalayan Red  
19. Kalijira  
20. Sona Masuri  

---

## Usage

**1.Run the Application:**
To start the application, run the following command in your terminal:
python main.py

**2.Upload Image:** 
Use the provided interface to upload a rice grain image.

**3.View Classification Result:**
The model will classify the uploaded image into one of the 20 rice varieties with 94% accuracy
