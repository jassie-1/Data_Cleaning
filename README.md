# Data_Cleaning
I have taken a dataset named "Netflix Shows and Movies - Exploratory Analysis" from Kaggle. It is named "netflix_titles_nov_2019". 
The duplicate values and rows with the missing values was removed using "drop_duplicates()" and "dropna()". 
The date format was changed from "Month date, year" to "dd-mm-yy" using "to_datetime" and "dt.dtrftime('%d %m %Y')".
The columns with large text data like "director", "cast" and "description" were dropped using "drop(<column name>)". 
Some mojibake characters were stripped from the "title" column using "strip()".
The index was reset and lastly the code file was converted to csv file using "pd.to_csv(<file_name>)".
The Code is in the "Data_Cleaning_code" file. The cleaned dataset file is named as "Cleaned_data".
