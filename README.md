## Google Play Store Apps Analytics 


This project aims to explore and analyze a dataset of Google Play Store apps  with 2.3 million+ Applications. The dataset used in this project is the part1 'Part1.csv.tar.gz' of the dataset provided by the author Gautham Prakash on Kaggle : (https://www.kaggle.com/gauthamp10/google-playstore-apps/) and his GitHub repository : https://github.com/gauthamp10/Google-Playstore-Dataset.git.
 
#### Project Questions :

    The following questions will be answered in this project:
- What is the number of installations of the 10 most Popular Apps?
- What are The Most Popular Apps?
- What are the Top 10 developers with the largest number of applications?
- Has the "Release" of Apps been affected by time?
- Has the "installs " of Apps been affected by time?- 
- What are the top 10 "Editors Choice" apps?

#### Requirements :

Python 3.11 or higher
Pandas
Matplotlib
Jupyter Notebook


#### Installation Instructions :

- On the shell terminal, navigate to the directory where you want to clone the repository.
- Clone the repository: https://github.com/rachid1122/Play-Store-Apps-Analytics.git
- Create a virtual environment: python -m venv venv
- Activate the virtual environment: source venv/scripts/activate (Windows) or source venv/bin/activate (Mac/Linux)
- Install required packages: pip install -r requirements.txt
- Start Jupyter Notebook: jupyter notebook
- Open Play-Store-Apps-Analytics.ipynb in Jupyter Notebook.
- Run the code cells to reproduce the analysis
- If there is any issue with the file size, run on the shell : $ git lfs install ; Then : $ git lfs track "*.psd"

#### Results :

   The analysis answers the questions as follows:
- The Most Popular Apps
- The sum of app installs by content rating (audience) is shown in a bar chart.
- the correlation between "installs" and "Rating"
- The top 10 "Editors Choice" apps are listed in a table.
- The number of apps "released" over time is shown in a line chart.

#### Project Testing :

The project has been tested on different computers with different OS to ensure that it runs properly. If you encounter any issues, please let me know by opening an issue on GitHub.
                      
#### Acknowledgments :

Thanks to Gautham Prakash for providing the Google Play Store App data on Kaggle and GitHub, all my Mentors and to the creators of Pandas, Matplotlib, Jupyter Notebook, and other modules used in this project.