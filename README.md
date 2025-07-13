# 🧺 Meesho-Style Customer Segmentation (KMeans + PPT Automation)

📌 **Project Overview**  
This project segments e-commerce customers for targeted marketing using **KMeans clustering** and generates **automated business reports** as PowerPoint slides, inspired by Meesho’s model of serving tier-2/3 users.

---

## 🎯 Objective

Segment customers based on behavioral and transactional attributes like:
- Preferred category
- Purchase frequency
- Region
- Loyalty score
- Return rate

🎯 Output: Business-focused recommendations per cluster + PowerPoint summary for stakeholders.

---

## 📷 Sample Output

### 🎞️ Auto-generated Slide:

![PCA Cluster Plot](https://github.com/student-kajal/customer-segmentation/blob/main/image.png)

> 📂 [View PPT File →](https://github.com/student-kajal/customer-segmentation/blob/main/customer_segmentation_meesho.pptx)

---

## 📦 Dataset

- **Synthetic dataset** designed to mimic Meesho’s consumer base.
- Includes:
  - Gender, Age, Region
  - Preferred Category
  - Purchase Frequency
  - Annual Income, Order Value
  - Loyalty & Return Rate

> ⚠️ Note: This data is generated for demo/learning purposes and can be replaced by real e-commerce data for production use.

---

## 🛠️ Tools Used

- `pandas`, `NumPy` for data wrangling
- `scikit-learn` → `KMeans`, `PCA`
- `matplotlib`, `seaborn` for cluster visualization
- `python-pptx` for **slide generation**

---

## 🚀 How to Run the Project

1. **Clone the repo**
   ```
   git clone https://github.com/student-kajal/customer-segmentation
   cd customer-segmentation
2. **Install requirements**
    pip install -r requirements.txt
3. **Run notebooks in order:**
   1_data_preprocessing.ipynb
   2_kmeans_segmentation.ipynb
   3_visualization_and_reporting.ipynb
4. **Final Output:**
   📁 outputs/customer_segmentation_meesho.pptx

   💼 Business Impact
   This segmentation enables:

🎯 Personalized marketing based on user preferences & loyalty

💰 Higher retention via targeted campaigns

📈 Growth strategy for underserved regions or categories

📦 Better inventory planning by understanding top-return clusters

| File/Folder              | Description                            |
| ------------------------ | -------------------------------------- |
| `data/customer_data.csv` | Input dataset                          |
| `notebooks/`             | All Jupyter notebooks                  |
| `outputs/`               | Final PPT slides + cluster summary CSV |
| `assets/`                | Images for README (PCA plots, slides)  |
| `README.md`              | You're reading it 😉                   |
---

## 👩‍💻 Author

**Kajal**

---

## 📜 License

This repository is meant for educational and portfolio purposes only.

This project demonstrates advanced analytics, automation, and business communication skills tailored to an e-commerce context like Meesho. It is well-suited for showcasing your technical and business acumen in analytics and business management roles.
