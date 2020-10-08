# Python Homework - Py Me Up, Charlie

Obejective:

Congrats you've made it!

You have just finish the Excel sheet and join the big data leagues. As we the start this journey of programming with Python. The homework assignment, we will be using the concepts that you've learned to complete the Python Challenges , The PyBank and The PyPoll.

Before You Start:

* Create a new repository for this project called `python-challenge`. **Do not add this homework to an existing repository**.

* Clone the new repository to your computer.

* Inside your local git repository, create a directory for both of the  Python Challenges. Use folder names corresponding to the challenges: **PyBank** and  **PyPoll**.

* Inside of each folder that you just created, add the following:

  * A new file called `main.py`. This will be the main script to run for each analysis.
  * A "Resources" folder that contains the CSV files you used. Make sure your script has the correct path to the CSV file.
  * An "analysis" folder that contains your text file that has the results from your analysis.

* Make sure you Push the above changes to GitHub or GitLab.

## PyBank

* In this assignment you with be creating a Python script that will be analyzing the financial records of your company. Then you will get a set of financial data called [budget_data.csv](PyBank/Resources/budget_data.csv). The dataset is composed of two columns: `Date` and `Profit/Losses`.
*First your task is be able to create a Python script that will analyze the records and you will calculate the following 

  * The total number of months that is included in the dataset

  * The net total amount of "Profit/Losses" over the entire period

  * The average of the changes in "Profit/Losses" over the entire period

  * The greatest increase in profits (date and amount) over the entire period

  * The greatest decrease in losses (date and amount) over the entire period

*Here is an example of how the analyst look like

  Financial Analysis
  ----------------------------
  Total Months: 86
  Total: $38382578
  Average  Change: $-2315.12
  Greatest Increase in Profits: Feb-2012 ($1926159)
  Greatest Decrease in Profits: Sep-2013 ($-2196167)
  ```

* Also, your final script should both print the analysis to the terminal and export a text file with the results.


PyPoll


 In this assignment, you are helping a small, rural town help with the vote counting process.

First You will be given a set of poll data called [election_data.csv](PyPoll/Resources/election_data.csv). The dataset is composed of three columns: `Voter ID`, `County`, and `Candidate`. Your assignment is to create a Python script that will analyze the votes and calculates the following:

  * The total number of votes cast

  * A complete list of candidates who received votes

  * The percentage of votes each candidate won

  * The total number of votes each candidate won

  * The winner of the election based on popular vote.

Here is a example of how the analysis looks like


  Election Results
  -------------------------
  Total Votes: 3521001
  -------------------------
  Khan: 63.000% (2218231)
  Correy: 20.000% (704200)
  Li: 14.000% (492940)
  O'Tooley: 3.000% (105630)
  -------------------------
  Winner: Khan


* In addition, your final script should both print the analysis to the terminal and export a text file with the results.


  

