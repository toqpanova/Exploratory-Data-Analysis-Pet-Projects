# Electric Vehicle Population Data Analysis

This repository contains a data analysis project using the "Electric Vehicle Population Data" dataset.

### Dataset  
The data was imported from a CSV file downloaded from [Google Drive](https://drive.google.com/file/d/172oRlGRIHck8CcuOHmLszw63VsfvigFg/view?usp=drive_link).

### Main Steps  
- Loaded data into a Pandas DataFrame.  
- Explored data structure using `.info()`, `.head()`, `.tail()`, and `.describe()`.  
- Identified columns with missing values and cleaned data by filling or dropping.  
- Selected specific rows and columns for closer inspection.  
- Analyzed statistical summary to identify that the 'Base MSRP' column has a 75th percentile value of 0.  
- Calculated correlation between 'Base MSRP' and 'Electric Range' and interpreted the result (low correlation of 0.11 means weak linear relationship).  
- Sorted data by 'Model Year' in ascending order.  
- Created a new column 'Electric Range Mapped' by categorizing 'Electric Range' into 'Low', 'Medium', and 'High'.  
- Exported cleaned and processed data to a new CSV file.

### Tools and Libraries  
- Python  
- Pandas  

This project helped me practice data loading, exploration, cleaning, basic statistics, correlation analysis, data transformation, and export — essential skills for data science workflows.
