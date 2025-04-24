0# 🎓 Student Engagement Analytics using SPSS Modeler

This project analyzes and predicts student engagement levels in an e-learning environment using IBM SPSS Modeler. It uses behavioral metrics such as logins, forum posts, quiz reviews, and assignment submission times to train predictive models and identify key patterns in learning behaviors.

---

## 📁 Dataset Overview

The dataset includes 7 features:

- `Student_ID`  
- `Logins`  
- `Content_Reads`  
- `Forum_Posts`  
- `Quiz_Reviews`  
- `Assignment_Submission_Time`  
- `Engagement_Level` (Target: High / Medium / Low)

---

## 🧠 Goals of the Project

- 🔍 Explore engagement patterns through data visualization  
- 🌲 Predict engagement levels using C5.0 Decision Trees  
- 🌀 Predict assignment submission time using Random Trees  
- 🧬 Forecast quiz reviews using Neural Networks  
- 📊 Split and validate data using a 70/30 partition strategy  
- 🎯 Perform multi-target modeling with a clean, branched flow  

---

## 🛠️ Project Structure

1. **Source Node** – Loads CSV dataset into SPSS Modeler  
2. **Type Node** – Assigns roles (Input, Target, None) to each field  
3. **EDA** – Graphs and plots visualize behavior vs. engagement  
4. **Partition Node** – Splits data (70% Train / 30% Test)  
5. **Modeling Nodes**:  
   - ✅ `C5.0` → Engagement Level Prediction  
   - ✅ `Random Trees` → Assignment Submission Time  
   - ✅ `Neural Net` → Quiz Review Forecasting  
6. **Output Nodes** – Evaluate performance, accuracy, RMSE, confusion matrix  

---


Each model uses the partitioned dataset and includes performance evaluations.

---

## 💡 Key Learnings

- Structured flow-based modeling using SPSS  
- Multi-model predictive analysis with nominal and continuous targets  
- Visual data storytelling using EDA graphs  
- Application of real-world educational data for insights  

---

## 🧾 Requirements

- IBM SPSS Modeler (v18 or later)  
- Dataset in `.csv` format  

---

## 📌 How to Run

1. Open SPSS Modeler  
2. Import the `.csv` file via the **Var. File** or **CSV Source Node**  
3. Follow the node pipeline as described  
4. Run the stream and visualize output metrics  
5. Analyze charts and model performance  

---

## 📬 Contact

👤 Author: *Kitten*  
📧 Reach out for collaboration, feedback, or academic discussions  

---

## 📃 License

This project is for academic and educational purposes. Attribution appreciated.



