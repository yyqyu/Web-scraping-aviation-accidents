安装
python2.7
apt install -y python-pip
pip install geopy 

pip install textblob

pip install nltk==3.1

运行
python /src/main.py



Practice 1: Web scraping
Description
This practice has been carried out under the context of the subject Typology and data life cycle,belonging to the Master's Degree in Data Science of the Universitat Oberta de Catalunya. In it, web scraping techniques are applied using the Python programming language to extract data from the PlaneCrashInfo web and generate a dataset.

Team members
The activity has been carried out individually by Teguayco Gutiérrez González.

Source code files
src/main.py: entry point to the program. Starts the scraping process.
src/scraper.py– Contains the implementation of the AccidentsScraper class whose methods generate the dataset from the PlaneCrashInfoonline database.
src/reason_classifier.py– Contains the implementation of the class that is responsible for assigning a cause to a given accident summary. To do this, use the TextBlob library.
Resources
Lawson, R. (2015). Web Scraping with Python. Packt Publishing Ltd. Chapter 2. Scraping the Data.
Mitchel, R. (2015). Web Scraping with Python: Collecting Data from the Modern Web. O'Reilly Media, Inc. Chapter 1. Your First Web Scraper.
