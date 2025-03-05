# Movie-Rating-Analysis
Exploratory Data Analysis and Advanced Visualization of Movie Ratings using Python, Seaborn, and Matplotlib.

### **📂 Project Structure**  
```
📦 Movie-Rating-Analysis
 ┣ 📜 ADVANCED_VISUALIZATION_MOVIE RATINGS.ipynb  # Jupyter Notebook with analysis
 ┣ 📜 Movie-Rating.csv                            # Dataset used in analysis
 ┣ 📜 README.md                                   # Project documentation
 ┗ 📜 requirements.txt                            # Python dependencies
```  

---

## **🚀 Key Topics & Concepts**  

### **1️⃣ Data Loading & Preprocessing**  
- Importing necessary libraries (`pandas`, `seaborn`, `matplotlib`)  
- Loading the dataset and checking its structure (`.head()`, `.info()`, `.describe()`)  
- Handling missing values (if any)  

### **2️⃣ Exploratory Data Analysis (EDA)**  
- **Understanding Dataset Features:**  
  - `Film`: Movie title  
  - `Genre`: Movie category (Action, Comedy, Drama, etc.)  
  - `CriticRatings`: Rotten Tomatoes critic score (0-100)  
  - `AudienceRatings`: Audience score (0-100)  
  - `BudgetMillion`: Movie budget in millions  
  - `Year`: Release year  

### **3️⃣ Data Visualization with Seaborn & Matplotlib**  

#### **🔹 Joint Plots (Critic Ratings vs. Audience Ratings)**  
- Helps visualize **correlation** between critic and audience ratings  
- Identifies **outliers** where audience and critics disagree  

#### **🔹 Histograms & KDE Plots**  
- **Understanding Audience & Critic Ratings Distribution**  
- Checking whether ratings follow a **normal distribution**  
- Identifying **skewness** in ratings  

#### **🔹 Box Plots & Violin Plots (Genre-based Analysis)**  
- Helps compare **critic vs. audience ratings** for different genres  
- Detecting **outliers** in movie ratings  
- **Comedy and Action** tend to have **more spread-out ratings**  

#### **🔹 Pair Plots**  
- Shows relationships between **Critic Ratings, Audience Ratings, Budget, and Year**  
- Helps visualize **patterns between variables**  

#### **🔹 FacetGrid Visualizations**  
- Compares **Critic Ratings vs. Audience Ratings** across different genres  
- Analyzes trends in **ratings over multiple years**  

