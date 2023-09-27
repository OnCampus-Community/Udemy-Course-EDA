# Udemy Top 5K Courses 2022 Project
This project analyses a dataset containing information on the top 5,000 courses offered on Udemy in 2022. The data was obtained from Kaggle. The dataset contains 18 columns, including the course name, instructor, course description, average rating, reviews count, course duration, lectures count, level, prices, students count, and course flag (indicating if it's a bestseller).

## Libraries used
pandas

numpy

seaborn

matplotlib

## Data Cleaning
The dataset was cleaned to make it easier to work with. This involved removing irrelevant columns, filling missing values, and cleaning up the data in some columns.

## Data Analysis
Exploratory data analysis was performed on the cleaned dataset to gain insights into the top courses offered on Udemy in 2022. The following questions were answered:

1. What is the distribution of courses by level?

2. What is the distribution of course prices after discount?

3. What is the average rating of the courses?

4. What is the distribution of courses by instructor?


## How to run:
#### Step 1: Clone the Repository
Explain how users can clone your project's GitHub repository to their local machine using the git clone command.
```
git clone https://github.com/OnCampus-Community/Udemy-Course-EDA.git

cd Udemy-Course-EDA
```
#### Step 2: Create a Virtual Environment
Guide users on creating a virtual environment in their project directory. Explain the benefits of using virtual environments to isolate dependencies.

``
virtualenv myenv
``
#### Step 3: Activate the Virtual Environment
Show users how to activate the virtual environment depending on their operating system (Windows, macOS, or Linux).
``````
# Windows
myenv\Scripts\activate

# macOS and Linux
source myenv/bin/activate
``````
#### Step 4: Install Project Dependencies
Explain how to install the project dependencies from the requirements.txt file.
The requirement file in this project based on jupyter notebook.
``````
pip install -r requirements.txt
``````
#### Step 5: Run the Project
Provide instructions on how to run your project. Include any specific commands or configuration that users need to know.
## Results
The results of the analysis show that most courses are geared towards beginners, with the majority of courses priced between E£10 and E£50 after discount. The average rating of the courses is 4.0, with a majority of the courses being taught by a small number of instructors.

## Conclusion
This project provides an overview of the top 5,000 courses offered on Udemy in 2022, including insights into the level, price, rating, and instructors of the courses. This information can be useful for students and instructors looking to choose or create courses on the platform.

## Usage
To use this project, simply run the code in a Jupyter Notebook or a Python environment. The data used in the project can be found on Kaggle.
