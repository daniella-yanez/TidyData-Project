**# Tidy Data Project**  

### **Project Overview**  
This project focuses on restructuring a dataset of Olympic medalists from the 2008 Olympics into a **tidy format**, following **tidy data principles** as outlined by Hadley Wickham. The goal is to:  
  **Reshape the dataset** for improved analysis and visualization.  
  **Clean and organize the data** by removing duplicates, handling missing values, and categorizing medals.  
  **Explore the data** through visualizations using Seaborn and Matplotlib.  

### ** Dataset Description**  
- **Source**: The dataset contains information on Olympic medalists from 2008, including their name, sport, gender, and medal type.  
- **Preprocessing Steps**:  
    **Data Cleaning**: Removed duplicates and missing values.  
    **Data Transformation**: Used `.melt()` to reshape the data.  
    **Feature Engineering**: Extracted gender and sport from a combined column.  
    **Categorization**: Converted "Medal" into an ordered categorical variable.  

### ** How to Run the Notebook**  
#### ** Prerequisites**  
Ensure you have the following Python libraries installed:  
```bash
pip install pandas matplotlib seaborn jupyter
```
#### **Steps to Run**  
1. Clone this repository:  
   ```bash
   git clone <repository_link>
   cd TidyData-Project
   ```
2. Open Jupyter Notebook:  
   ```bash
   jupyter notebook
   ```
3. Run `TidyData-Project.ipynb` to execute the data cleaning and visualization steps.  

### ** Visual Examples of Untidy Dataset**  
Issues: 
- When inspecting the data, we see that there are 70 columns, not including the name column, for specific sports divided by men's and women's sports. The width of the dataset is one aspect that makes this dataset unreadable. 

- Another factor is that there are only three potential medals: gold, silver, and bronze. However, due to the unmanageable amount of columns, keeping track of the gold, silver, or bronze medals should be easier.

- Any possible question about the medalists is tackled by the insane mess of this dataset that makes finding any information for an individual, a sport, or a medal hard to find.

- Below is an example of how with 30 rows and 4 columns, we only learn about 3 medals given. Absolute Chaos.
 <img width="916" alt="Screenshot 2025-03-18 at 7 25 28 AM" src="https://github.com/user-attachments/assets/55b6659c-d2ca-463b-8dbc-f820a00d4011" />

### ** Visual Examples of Improved, Tidy Dataset**  

<img width="350" alt="Screenshot 2025-03-18 at 7 28 48 AM" src="https://github.com/user-attachments/assets/bc9bf35f-8aec-4b99-a25d-3e97aa9fac0c" />


### **References**  
- [Tidy Data Paper by Hadley Wickham](https://vita.had.co.nz/papers/tidy-data.pdf)  
- [Pandas Cheat Sheet](https://pandas.pydata.org/Pandas_Cheat_Sheet.pdf)  

---
