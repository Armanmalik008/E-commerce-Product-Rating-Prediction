# 🛒 E-commerce Product Rating Prediction

![Uploading zack-yeo-dNb1rjP0auw-unsplash.jpg…]()
![Uploading zack-yeo-dNb1rjP0auw-unsplash.jpg…]()
![Uploading zack-yeo-dNb1rjP0auw-unsplash.jpg…]()
![Uploading zack-yeo-dNb1rjP0auw-unsplash.jpg…]()

## 📌 Overview

This project aims to predict the **ratings of products on an E-commerce platform** using features like product title, description, brand, and price. Accurate predictions can help sellers and platforms improve product presentation and customer satisfaction.

## 📂 Project Structure

- `E-commerce Product Rating Prediction.ipynb`: Contains full pipeline – preprocessing, feature engineering, model training, and evaluation.

## 🔍 Problem Statement

Given structured and textual product data, predict the product's **average rating** (continuous value).  
This is framed as a **regression** task.

## 🧰 Technologies Used

- Python (Jupyter Notebook)
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn
- ML Frameworks: XGBoost, LightGBM, CatBoost
- NLP: TF-IDF, CountVectorizer

## 📊 Workflow

1. **Data Cleaning**
2. **EDA**
3. **Feature Engineering**
4. **Model Training**
5. **Evaluation**

## 🏆 Results

| Rank | Model           | RMSE   | Remarks        |
|------|------------------|--------|----------------|
| 🥇 1st | **Random Forest**  | **0.6896** | ✅ Best performance |
| 2nd  | XGBoost         | 0.6898 | Very close     |
| 3rd  | CatBoost        | 0.6967 | Good           |
| 4th  | LightGBM        | 0.7011 | Moderate       |
| 5th  | KNN Regressor   | 0.7633 | Underperformed |

**✅ Top Performer:** `Random Forest Regressor` with the lowest RMSE of **0.6896**

## 🚀 Future Enhancements

- Integrate review sentiment analysis
- Build a Flask or Streamlit web app
- Deploy API with Docker or FastAPI

## 🙋‍♂️ Author

**Arman Ghanchi**  
🏆 **Secured 1st Rank in the MachineHack AI Hackathon**  
🔗 [LinkedIn Achievement Post](https://www.linkedin.com/posts/arman-ghanchi-9b9422315_secured-rank-1-in-machinehack-ai-hackathon-activity-7339345774536716289-WlWJ?utm_source=share&utm_medium=member_desktop&rcm=ACoAAE_5dR0BVoE1abKDT4ISJT5ycSHBG698LxM)

---

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
