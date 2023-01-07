# ratio-applicant-applications
This code gives ratio of applications and applicant for two subsidie rounds. It answers: How often do applications come from the same researcher? Is this a new topic or a more or less resubmission of a previously rejected topic? Based on the title or summary give an indication.

## Code
This code is for analyzing data from excel files containing information about grant proposals. It allows the user to import excel files using a browse button and then processes the data to find various statistics about the proposals. This includes finding the number of unique applicants who have submitted proposals, finding the number of applicants who have submitted multiple proposals, and finding the number of times that applicants have resubmitted the same proposal title. The code also generates a plot showing the ratio of applications to applicants.

The code is used for analyzing applications submitted to a grant program. It begins by importing various modules including xlsxwriter, scipy, numpy, and pandas. It also uses tkinter to allow the user to select an Excel file for analysis. The selected file is then read in as a pandas dataframe and renamed using the fifth row as the header. The data is cleaned by removing any rows where the applicant has withdrawn their application and resetting the index. The code then identifies applicants who have submitted multiple applications and creates a new dataframe with this information. The number of applications per applicant is plotted using seaborn and matplotlib. The code also checks for applicants who have resubmitted the same application title and creates a new dataframe with this information. The code then outputs the number of unique applicants and the number of unique applicants who have resubmitted the same application title.

## How to use
To use the code, follow these steps:

1. Download the code and open it in your preferred Python environment.

2. Import the necessary libraries (e.g. pandas, matplotlib).

3. Use the browse button to select the excel file you want to analyze.

4. Run the code to process the data and generate the desired statistics and plot.

Note: The excel file should contain columns for the applicant name and proposal title. The code expects these columns to be named "Applicant" and "Title", respectively. If your file has different column names, you will need to adjust the code accordingly.
