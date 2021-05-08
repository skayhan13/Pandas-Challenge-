# Pandas-Challenge
In this assignment, we were given the task of analyzing data for a school district using the Pandas software library within Python.  Pandas is a very powerful, intuitive and popular tool.  It is a declared favorite for many data scientists.

After analyzing the data, I can make two conclusions, which would have not seemed true to me at the onset of this assignment:
1.  The more money that is spent on each student, the worse their average test scores.  This seems counterintuitive but is supported by the dataframe called "scores_by_spending"

2.  The top-performing schools vs. the bottom-performing schools by overall student's passing percentage (which means a student must recieve a 70% or greater on math AND reading tests) showed that the top five performing schools were all charter schools.  While the top five performing schools were all district schools.  This can be seen in the "top_performing_schools" dataframe and the "bottom_performing_schools" dataframe.

Extensive directions for this assignment can be found below:

Background
The data dive continues!
Now, it's time to take what you've learned about Python Pandas and apply it to new situations. For this assignment, you'll need to complete one of two (not both)  Data Challenges. Once again, which challenge you take on is your choice. Just be sure to give it your all -- as the skills you hone will become powerful tools in your data analytics tool belt.

Before You Begin


Create a new repository for this project called pandas-challenge. Do not add this homework to an existing repository.


Clone the new repository to your computer.


Inside your local git repository, create a directory for the Pandas Challenge you choose. Use folder names corresponding to the challenges: HeroesOfPymoli or  PyCitySchools.


Add your Jupyter notebook to this folder. This will be the main script to run for analysis.


Push the above changes to GitHub or GitLab.

Option 2: PyCitySchools

Well done! Having spent years analyzing financial records for big banks, you've finally scratched your idealistic itch and joined the education sector. In your latest role, you've become the Chief Data Scientist for your city's school district. In this capacity, you'll be helping the  school board and mayor make strategic decisions regarding future school budgets and priorities.
As a first task, you've been asked to analyze the district-wide standardized test results. You'll be given access to every student's math and reading scores, as well as various information on the schools they attend. Your responsibility is to aggregate the data to and showcase obvious trends in school performance.
Your final report should include each of the following:

District Summary

Create a high level snapshot (in table form) of the district's key metrics, including:

Total Schools
Total Students
Total Budget
Average Math Score
Average Reading Score
% Passing Math (The percentage of students that passed math.)
% Passing Reading (The percentage of students that passed reading.)
% Overall Passing (The percentage of students that passed math and reading.)




School Summary

Create an overview table that summarizes key metrics about each school, including:

School Name
School Type
Total Students
Total School Budget
Per Student Budget
Average Math Score
Average Reading Score
% Passing Math (The percentage of students that passed math.)
% Passing Reading (The percentage of students that passed reading.)
% Overall Passing (The percentage of students that passed math and reading.)




Top Performing Schools (By % Overall Passing)

Create a table that highlights the top 5 performing schools based on % Overall Passing. Include:

School Name
School Type
Total Students
Total School Budget
Per Student Budget
Average Math Score
Average Reading Score
% Passing Math (The percentage of students that passed math.)
% Passing Reading (The percentage of students that passed reading.)
% Overall Passing (The percentage of students that passed math and reading.)




Bottom Performing Schools (By % Overall Passing)

Create a table that highlights the bottom 5 performing schools based on % Overall Passing. Include all of the same metrics as above.


Math Scores by Grade**

Create a table that lists the average Math Score for students of each grade level (9th, 10th, 11th, 12th) at each school.


Reading Scores by Grade

Create a table that lists the average Reading Score for students of each grade level (9th, 10th, 11th, 12th) at each school.


Scores by School Spending

Create a table that breaks down school performances based on average Spending Ranges (Per Student). Use 4 reasonable bins to group school spending. Include in the table each of the following:

Average Math Score
Average Reading Score
% Passing Math (The percentage of students that passed math.)
% Passing Reading (The percentage of students that passed reading.)
% Overall Passing (The percentage of students that passed math and reading.)




Scores by School Size

Repeat the above breakdown, but this time group schools based on a reasonable approximation of school size (Small, Medium, Large).


Scores by School Type

Repeat the above breakdown, but this time group schools based on school type (Charter vs. District).

As final considerations:

Use the pandas library and Jupyter Notebook.
You must submit a link to your Github/Git Lab repo that contains your Jupyter Notebook.
You must include a written description of at least two observable trends based on t