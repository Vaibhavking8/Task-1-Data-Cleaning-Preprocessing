# Task-1-Data-Cleaning-Preprocessing

This project demonstrates essential data preprocessing steps on the Titanic dataset.

## Steps Performed

1. **Import & Explore Dataset**
   - Checked for null values and data types.
   - Identified missing values in `Age`, `Cabin`, and `Embarked`.

2. **Handle Missing Values**
   - `Age`: Filled with **median** to avoid skew from outliers.
   - `Cabin`: Dropped due to excessive missing values.
   - `Embarked`: Filled with **mode**.

3. **Encode Categorical Features**
   - `Sex`: Label encoded (`male=1`, `female=0`).
   - `Embarked`: One-hot encoded.

4. **Standardize Numerical Features**
   - Used `StandardScaler` on `Age`, `Fare`, `SibSp`, `Parch`.

5. **Outlier Detection & Removal**
   - Visualized outliers using **boxplots**.
   - Removed outliers using **IQR (Interquartile Range)** method.


