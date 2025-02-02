1. **Data Loading**:  
   - Loaded the dataset from an Excel file and inspected its structure to identify relevant columns.

2. **Extracting Likert Scale Data**:  
   - Identified survey questions that used a Likert scale (columns starting from **"1:" to "10:"**).  
   - A new DataFrame (`df_likert_filtered`) was created containing only these Likert scale responses.

3. **Converting Likert Scale to Numeric Values**:  
   - Mapped textual Likert responses (e.g., **"5-Strongly Agree"**) to corresponding numeric values (**1 to 5**).  
   - This resulted in a numeric DataFrame (`df_likert_numeric_filtered`), making statistical analysis possible.

4. **Box Plot Visualization**:  
   - Generated a **box plot** of the numeric Likert scale responses.  
   - The x-axis labels were adjusted for better readability by increasing the font size.

5. **Outlier Detection**:  
   - Applied the **Interquartile Range (IQR) method** to detect outliers in the Likert scale responses.  
   - Outliers were extracted and displayed in a structured format for further investigation.

This analysis helped in **understanding the distribution, variability, and potential anomalies** in the survey responses regarding UAV delivery. 
![output](https://github.com/user-attachments/assets/2a2f926b-4c1c-4350-a55f-976a12337f2e)
