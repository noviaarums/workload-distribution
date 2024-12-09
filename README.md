# workload-distribution
Providing visualization charts about review and commit workload distribution of a GitHub repository project

## DESCRIPTION
- This project analyzes review and commit data to provide insights into the distribution of works across contributors.
- This project uses 10 GitHub repository including:
	1. scrapy/scrapy
	2. fastapi/fastapi
	3. psf/requests
	4. pallets/flask
	5. celery/celery
	6. python-pillow/Pillow
	7. python-poetry/poetry
	8. psf/black
	9. pydantic/pydantic
	10. encode/django-rest-framework

## FEATURES
- Data Analysis : Analyzes review and commit data for contributors
- Visualization : Generates bar charts to visualize the number of reviews and commits distribution 
- CSV file support : Imports review and commit data from CSV files
- Yearly Analysis : Filter commits and reviews data by year (e.g., 2024)
- Top Contributors: Identifies and displays the top 20 contributors in terms of commits and reviews

## HOW TO RUN 

USING GOOGLE COLABORATORY

Prerequisites
1. Ensure you have a Google account to access the Google Colaboratory

Running the Project on Google Colab
1. Open Google Colab
2. Upload the Notebook
   - Upload the provided .ipynb files from this repository to Google Colab
3. Run the Notebook
   - Execute each code cell sequentially
   - Firstly execute reviewFetch.ipynb and commitFetch.ipynb files by writing down the address of GitHub repository project that will be analyzed in the provided space
   - After that, there will be results in CSV files contain review and commit data
   - Upload those CSV files into each other python files for getting the visualization charts and other useful information about numbers to analysis process
   - reviewVisualization.ipynb and commitVisualization.ipynb will give visualization about review and commit distribution respectively throughout the project history. And for getting the visualization in “the last year” or a specific year, the last code cell will provide it.
   - contributors.ipynb will give visualization of combination between review and commits work happened in the project history.
   - By using those CSV files (review and commit CSV files), execute those visualization files by writing down the name of CSV files in the provided space

Expected Output
1. Fetching data result in CSV files (for reviews and commits data)
2. Number of reviewers, number of reviews, number of committers, number of commits throughout the project history
3. Visualization charts of review works distribution, commit works distribution, and the combination of top 20 usernames in reviewing and committing codes throughout the project history
3. Number of reviewers, number of reviews, number of committers, number of commits in 2024 (refers to “the last year”)
4. Visualization charts of review works distribution, commit works distribution, and the combination of top 20 usernames’ committers in reviewing codes throughout the project history


## INSIGHTS
Please read all files below:
- Report-Workload Distribution.pdf: about resulting charts and insights in details
- Summary-Conclusion-Workload Distribution.pdf: about summary of insights and final conclusion of all projects

