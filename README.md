# Stack-Overflow

The python libraries used in this project are numpy, pandas, math, sklearn, and matplotlib. 

The motivation for the project is to explore the stack overflow annual survey for software developers to shed light on software developer's salaries, love for problem solving, and determining their salaries based on their love for problem solving. The three business questions are as follows:
1) What percentage of the developers love problem solving? 
2) What is the average salary of a developer? 
3) Can we predict the salary of developer who loves to solve problems? 

We utilized the Stack Overflow data set from its 2019 annual survey. Stack Overflow is a knowledge market that serves as a question and answer site for professional and enthusiast programmers. Every year, Stack Overflow conducts a massive survey of people on the site, covering all sorts of information like programming languages, salary, code style and various other information. In 2019, they amassed more than 64,000 responses fielded from 213 countries.

To build the AI/ML model to predict programmers’ salaries based on their attitudes towards problem solving, we prepared the data through cleaning, removing missing values, mutation, and changing categorical variables to numerical for the machine to better understand and model the data. Then we built our model using the linear regression in Python. The independent variable was the attitude towards problem solving, and the dependent variable was salary.

The result for each question is as follows:
1) What percentage of the developers love problem solving? Graph showcased that about 35% who strongly love it, and 20% who love it for a total of 55%.
2) What is the average salary of a developer? The result was $56,298 showcased in a descriptive statistics table.
3) Can we predict the salary of developer who loves to solve problems? Yes, $50,802

This project includes 3 files. This ReadMe file, the jupyter notebook, and a link to the blog post.
  - The Blog post file has a link to a blog post that communicates the project to non-technical readers.
  - The ReadMe file with the motivation for the project, the files in the repository with a small description of each, a summary of the         results of the analysis, and necessary acknowledgements.
  - The jupyter notebook includes executable code that was used for this project with proper comments.
 
  
Acknowledgements: We would like to thank Stack Overflow for making the dataset of their annual survey publicly available.
