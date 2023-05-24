# Dummy_dataset for Cast Social

The code begins by importing the necessary libraries: pandas, random, and Faker. pandas is used for data manipulation and analysis, random for generating random values, and Faker for generating fake data.

The generate_dummy_dataset function is defined. It takes two parameters: num_records, which specifies the number of records to generate, and columns, which represents the list of column names for the dataset.

Inside the function, an empty list called data is created to store the generated records.

A loop is used to generate random data for each record. Within the loop, various variables are generated using the fake object from the Faker library, along with random values using the random module.

The generated data for each record is appended as a row to the data list.

After the loop, the data list is converted into a Pandas DataFrame using the pd.DataFrame function. The columns parameter is used to assign column names to the DataFrame.

The generated DataFrame is returned from the function.

The columns variable is defined, representing the list of column names for the dataset.

The generate_dummy_dataset function is called with the desired number of records 2million) and the columns list.

The resulting dummy dataset is saved to a CSV file named "dummy_dataset.csv" using the to_csv method of the DataFrame.

The code utilizes the Faker library to generate random values for each column, allowing you to create a dummy dataset with realistic-looking data.
