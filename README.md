# Analyzing A/B Test Results of an E-commerce Website

This project was developed for the Udacity Data Analyst Nanodegree in order assure the complete understanding of the statistics lessons.

# Table of Contents
1. [Data](#data)
2. [Project Goals](#goals)
3. [Prerequisites to contribute](#requisites)
4. [How to visualize the study](#visualize)
5. [License](#license)


<a name="data"></a>
## Data

### ab_data.csv
In order to answer all questions, the `ab_data.csv` was provided with information about the user experience on the website. Below you can find the information about each column in this dataframe:

* **user_id:** a unique identifier for each user.
* **timestemp:** the time the user accessed the landing page (`yyyy-MM-dd HH:mm:ss.SSSSSS` format).
* **group:** the group that the visitor belongs, either `control` (the ones that should receive the old page) or `treatment` (the ones that should receive the new page).
* **landing_page:** the page that the user received, either `old_page` or `new_page`.
* **converted:** if the user converted or not, '1' being that the user converted.

### country.csv
To access the information regarding the user's nationality, we must use `country.csv`. Below you can find the information about each column in this dataframe:

* **user_id**: a unique identifier for each user (same as the user_id on `ab_data.csv`).
* **country**: the respective user's country.

<a name="goals"></a>
## Project Goals
The main goal of the project is to help the company decide if they should implement the new page, keep the old page, or perhaps run the experiment longer to make their decision using Python 3.

<a name="requisites"></a>
## Prerequisites to contribute
After downloading all the necessary files present in this repository, you must choose between one of the following methods. Choose wisely ;)

### Method 1
If you want to contribute, this project requires **Python 3** and its following libraries installed:

* [Pandas](https://pandas.pydata.org/)
* [Numpy](https://numpy.org/)
* [Matplotlib](https://matplotlib.org/)
* [Statsmodels](https://www.statsmodels.org/stable/index.html)

Besides, you also need to install a software to use [Jupyter Notebook](https://jupyter.org/).  
I recommend downloading [Anaconda](https://www.anaconda.com/) (Python distribution), which already has all the necessary modules and Jupyter Notebook installed.

### Method 2
You can also decide to use [Google Colab](https://colab.research.google.com/), in this case, all you have to do is open the notebook (`.ipynb` file) on Google Colab with your account.

<a name="visualize"></a>
## How to visualize the study
You can just download the files and open the `.html` file on your browser, feel free to give feedbacks :)

<a name="license"></a>
## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details


