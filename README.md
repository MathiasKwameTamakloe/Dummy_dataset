# Dummy_dataset for Cast Social

The provided dataset contains the following columns:

Video ID: A unique identifier for each video.

User ID: A unique identifier for the user who uploaded the video.

Video Title: The title of the video.

Video Description: A description of the video.

Video Tags: A list of tags that describe the video.

Views: The number of times the video has been viewed.

Likes: The number of times the video has been liked.

Comments: The number of times the video has been commented on.

Age: The age of the user who uploaded the video.

Gender: The gender of the user who uploaded the video.

Shares: The number of times the video has been shared.

Duration: The length of the video in seconds.

Hashtags: A list of hashtags that are associated with the video.

Timestamp: The date and time when the video was uploaded.

Location: The location where the video was uploaded.

User Followers: The number of followers the user who uploaded the video has.

User Following: The number of users the user who uploaded the video is following.

User Likes: The number of times the user who uploaded the video has liked other videos.

User Comments: The number of times the user who uploaded the video has commented on other videos.

User Shares: The number of times the user who uploaded the video has shared other videos.

You can access the zip file for the Dummy_dataset here; https://drive.google.com/file/d/1-AhVyjYG-EF_6QPbp9Y6jkTx3amBRUna/view?usp=drive_link

CSV file: https://drive.google.com/file/d/1-7EZOxzHmL_oVMbGAukGoay4dRA_snv0/view?usp=drive_link

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
