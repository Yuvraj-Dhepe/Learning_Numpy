# Learning Numpy
Includes all the resources and files helpful for doing the numpy course.

### Structure of the folders
- Exercise: Includes all the exercise .ipynb files per episode in the course.
It was practiced simultaneously doing the course.
- Notes: Includes all the examples covered in the course in form of .ipynb format.
- Solutions: These are the standard solutions for the exercises given by the creator of the course.
- Templates: Includes all the examples solved by me from the course.
- Data: Includes all the data files in .csv format necessary for doing the course 
examples and exercises.

### Practical example covered in course.
### All the tasks that were done as a data analyst in preprocessing the data in example are as follows:
1) The analyst is provided with the necessary changes in form of a file  required in the dataset and also the dataset.
    - In this preprocessing following bits need to be done:
        + Convert the data in the quantified form i.e. every value is numeric, for this we make categories and assign numbers or have positive, negative connotations or simple 0 and 1 as the values.
        + There is a need to convert USD values to EUR currency.
        + The data has to be clean and not possessing outliers and missing values for the model to run.
        + Filling values is done keeping in mind we are creating a CRM: Credit risk model for a bank so that we can find the defaulters on their details and not provide give them loans.
        + Thus, the values are filled keeping in mind the creditworthiness of a customer.
            1) We need to be extreme risk-averse and distrustful.
            2) Missing information suggests foul play.
            3) If the information isn't available, we'll just assume the worst.
2) It's always a good idea to have the alterations done on paper before being done on data, this will save a lot of time in the long run.
3) The following tasks are performed on the data on a brief:
    + Importing and Examining Data.
    + Splitting the data to strings and numeric values and headers. This allows easy handling of the data.
    + Manipulating the data, by removing missing values, converting the strings to the equivalent numeric values on the base of the above instructions.
    + Creating checkpoints in the midway when major tasks like manipulating strings is done, then numeric cols is done etc.
    + Finally, we may sort the dataset and combine all the split data into a single variable, ready to be imported into the data file.
