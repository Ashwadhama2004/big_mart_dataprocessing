big_mart_preprocessing
```markdown
# Sales Data Analysis and Preprocessing

This project focuses on analyzing and preprocessing a sales dataset to handle missing values, perform exploratory data analysis (EDA), and encode categorical features for machine learning models.

## Dataset

The dataset used in this project contains various features related to items sold in different types of outlets. It includes information like `Item_Weight`, `Item_Fat_Content`, `Item_Visibility`, `Item_Type`, `Outlet_Type`, etc.

### Key Steps in Data Preprocessing

1. **Handling Missing Values**:
   - The `Item_Weight` feature had missing values, which were filled with the mean of the column.
   - The `Outlet_Size` feature had missing values, which were filled based on the mode of the corresponding `Outlet_Type`.

2. **Exploratory Data Analysis (EDA)**:
   - Used seaborn and matplotlib to visualize the distribution of numerical features and the count of categorical features.
   - Analyzed the distribution of features such as `Item_Weight`, `Item_Visibility`, `Item_MRP`, `Outlet_Establishment_Year`, `Item_Fat_Content`, etc.

3. **Label Encoding**:
   - Encoded categorical variables such as `Item_Fat_Content`, `Item_Type`, `Outlet_Identifier`, `Outlet_Size`, `Outlet_Location_Type`, and `Outlet_Type` using `LabelEncoder` from sklearn.

## Libraries Used

- `pandas` for data manipulation.
- `numpy` for numerical operations.
- `seaborn` and `matplotlib` for data visualization.
- `scikit-learn` for preprocessing and model building.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/Ashwadhama2004/sales-data-analysis.git
   ```
2. Install the necessary dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the code in a Jupyter Notebook or your preferred Python environment.

## Contributions

Contributions are welcome! Please open a pull request or file an issue if you have suggestions or improvements.

```

"https://github.com/Ashwadhama2004/sales-data-analysis.git"` 
