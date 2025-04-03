# Data-Transformation-using-Python
- Short Description:
This project focuses on transforming and analyzing a YouTube dataset using Python. It includes data preprocessing, handling missing values, extracting relevant data, and analyzing channel type distributions.
## Getting Started
Before running the project, ensure you have the following installed:
- Python 3.x Or Anaconda
- Jupyter Notebook or any Python IDE
- Required libraries: pandas, numpy
## Running the tests
1. Importing Libraries
- pandas for dataset handling and analysis.
- numpy for numerical operations.

2. Loading the Dataset
- The dataset path is stored in a variable (youtube_dataset.csv).

- encoding='unicode_escape' ensures proper interpretation of special characters.

- .head() and .info() functions are used to inspect the dataset.

3. Handling Missing Values
- The channeltype column's missing values are filled using its mode.

4. Extracting the Top 1000 Channels
- The first 1000 rows are stored in a new DataFrame called Top_1000_Channels.

5. Analyzing Channel Type Distribution
- A function Channel_type_distribution is created to calculate the frequency distribution of unique values in the channeltype column.
- The function is applied to Top_1000_Channels for analysis.
- The distribution results are printed.

6. Saving Processed Data
- The Top_1000_Channels DataFrame is saved as Top_1000_Youtube_Channels.csv for further use.
## Deployment
To deploy the project:
- Ensure all dependencies are installed.
- Run the Jupyter Notebook or Python script containing the transformation logic.

## Authors
Shivam Choudhary

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgement
- Prof. Omar al-trad
- My teammates
