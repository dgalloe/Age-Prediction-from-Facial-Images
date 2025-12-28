# Age-Prediction-from-Facial-Images
Developed a computer vision model to predict age from facial images using deep learning techniques. Implemented data analysis, neural network architecture design, and model evaluation to create an accurate age estimation system. Provided insights for improving facial recognition applications.

## 1. Objectives 🎯
- Analyze a dataset of facial images with age labels to understand data distribution
- Develop a deep learning model to predict age from facial images
- Handle class imbalance in age distribution through appropriate techniques
- Implement data augmentation strategies to improve model generalization
- Evaluate model performance using appropriate metrics for regression tasks
- Compare different neural network architectures for age prediction

## 2. Key Findings 🏆
- Dataset contains 7,591 facial images with corresponding age labels (1-100 years)
- Age distribution shows right skew with most subjects between 20-40 years old
- Mean age: 31.2 years, Median age: 29 years indicating younger population bias
- Significant class imbalance observed with fewer samples at extreme age ranges
- Data quality appears good with no missing values or duplicates in labels
- Image preprocessing and augmentation will be critical for model performance

## 3. Visualizations Included 🎨
- Histogram showing age distribution across the dataset
- Box plot displaying age statistics and identifying outliers
- Descriptive statistics summary of age variable
- Data quality checks (duplicates, missing values)
- Random image samples for visual inspection of data

## 4. Skills Demonstrated 🛠️
- Data Exploration: Statistical analysis of target variable distribution
- Data Quality Assessment: Checking for duplicates, missing values, and inconsistencies
- Data Visualization: Creating informative plots for understanding data characteristics
- Data Preprocessing: Planning image loading and augmentation strategies
- Problem Analysis: Identifying challenges in age prediction from facial images
- Technical Documentation: Clear notebook structure with explanatory comments

## 5. Technical Details 💻
- Programming Language: Python
- Main Libraries: pandas, matplotlib, seaborn, PIL, os, random
- Dataset: 7,591 facial images with age labels (1-100 years)
- Image Directory: /datasets/faces/final_files/
- Labels File: labels.csv with file_name and real_age columns
- Analysis Focus: Understanding age distribution and data characteristics
- Future Implementation: Generator-based image loading for memory efficiency

## 6. Installation and Usage
```bash
# Clone the repository
git clone https://github.com/yourusername/age-prediction-facial-images.git

# Navigate to project directory
cd age-prediction-facial-images

# Install required dependencies
pip install -r requirements.txt

# Run the analysis notebook
jupyter notebook DanielGallo_revisado.ipynb
