# AtliQ Hotels Data Analysis Project

This project involves analyzing various datasets related to AtliQ Hotels to derive insights about bookings, revenue, occupancy rates, and more. The analysis includes data cleaning, transformation, and generating visual and statistical insights.

## Project Structure

### 1. Data Import and Data Exploration

**Datasets:**
- `dim_date.csv`
- `dim_hotels.csv`
- `dim_rooms.csv`
- `fact_aggregated_bookings.csv`
- `fact_bookings.csv`

The project begins with importing and exploring these datasets to understand their structure and content. Key steps include:

- Reading data into dataframes using Pandas.
- Exploring the `fact_bookings` dataset for unique room categories and booking platforms.
- Analyzing hotel information such as category distribution and city-wise hotel counts.
- Exploring aggregate bookings to understand booking trends, capacity utilization, and more.

### 2. Data Cleaning

Data cleaning is crucial to ensure the accuracy and reliability of the analysis. The cleaning steps include:

- **Cleaning invalid guests**: Removing records with non-positive guest counts.
- **Outlier removal**: Identifying and removing outliers in revenue data.
- **Handling missing values**: Filling null values with appropriate substitutes, such as the median for capacity.

### 3. Data Transformation

Transformation steps include:

- **Creating new columns**: For example, calculating the occupancy percentage (`occ_pct`) in the `fact_aggregated_bookings` dataset.
- **Merging data**: Combining different datasets to create a comprehensive view for analysis.
- **Normalization and aggregation**: Applying these techniques where necessary.

### 4. Insights Generation

The final step involves deriving actionable insights from the data:

1. **Average occupancy rate per room category**
2. **Average occupancy rate per city**
3. **Occupancy comparison between weekdays and weekends**
4. **Occupancy analysis for June by city**
5. **Appending new data for August**
6. **Revenue realized per city**
7. **Month-by-month revenue analysis**

#### Exercises:
- **Print revenue realized per hotel type**
- **Print average rating per city**
- **Pie chart of revenue realized per booking platform**

## Usage

To run this project, you will need Python installed along with the Pandas library. Clone the repository, place the datasets in the appropriate folder, and run the script to perform the analysis.

## License

This project is licensed under the MIT License.
