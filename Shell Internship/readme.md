# 🌱 Crop and Fertilizer Recommendation System using Machine Learning: 

## 📌 Project Overview:
This project leverages Machine Learning to recommend the best crop and fertilizer based on soil composition, weather conditions, and nutrient levels. By analyzing these factors, the system helps farmers make data-driven decisions to optimize yield and resource use.

## ⚙️ Technologies Used
```bash
 * Python
 * NumPy, Pandas (Data Processing)
 * Matplotlib, Seaborn (Data Visualization)
 * Scikit-learn (Machine Learning)
 * Random Forest Classifier (Crop Recommendation)
 * Decision Tree Classifier (Fertilizer Recommendation)
```

## 📂 Dataset
This project uses two datasets:
1. Crop Recommendation Dataset - Contains soil nutrient levels (Nitrogen, Phosphorus, Potassium), temperature, humidity, and crop types.
2. Fertilizer Recommendation Dataset - Contains soil types, crop types, and environmental factors to suggest the best fertilizer.

## 🚀 Installation & Setup
1. Clone the repository: git clone https://github.com/your-username/crop-fertilizer-recommendation.git
2. cd Shell Internship
3. Install dependencies: pip install numpy pandas matplotlib seaborn scikit-learn
4. Run the Jupyter Notebooks:
    * Open Jupyter Notebook: jupyter notebook
    * Run the following notebooks:
    * crop.ipynb (Crop Recommendation System)
    * fertiliser.ipynb (Fertilizer Recommendation System)

## 📊 Methodology
1. Data Preprocessing:
* Handle missing values, normalize numerical data, and encode categorical features.
* Check for duplicate and null values.
  
2. Exploratory Data Analysis (EDA):
* Visualize distributions of features using histograms, scatter plots, and box plots.
* Compute feature correlations using a heatmap.
  
3. Model Training:
* Random Forest Classifier for crop recommendation
* Decision Tree Classifier for fertilizer recommendation
  
4. Evaluation:
* Assess model performance using accuracy scores and confusion matrices.
  
5. Prediction Function:
* Accepts user input and recommends the best crop and fertilizer based on soil conditions.

## 🔍 Usage
You can use the system to:
* Predict the best crop for a given soil and weather condition.
* Recommend the most suitable fertilizer based on soil nutrients.
  
## 📈 Future Improvements
* Integrate IoT-based real-time soil data collection.
* Enhance accuracy using Deep Learning techniques.
* Develop a user-friendly Web or Mobile App interface.
  

