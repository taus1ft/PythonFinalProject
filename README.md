Tausif Tamim \
CS-102-C \
Professor Marano \
Python Mini-Project

# Project Idea: Compare the number of Covid-19 cases in the U.S. to China's and Russia's every year while showing how COVID-19 was handled by some countries better than others.
\
Dataset from the WHO that gives Covid-19 datasets: https://data.humdata.org/dataset/coronavirus-covid-19-cases-and-deaths
Dataset that gives GDP per country: https://datahub.io/world-bank/ny.gdp.pcap.cd

**Explaining Part 1:**

We first install pandas. Pandas is a dictionary that  helps us visualize data into manny  forms such as graphs.
\
We then imported matplotlib. What this does it that it helps us plot the numbers in a useful way.
\
In general, pandas and matplotlib works together to give us really impressive graphs.

**Explaining Part 2:**

First we take all the sourcefiles we need, which I gave the link to previously. These are in the form of csv files, which are essentially characterized as data sheets.

We then read the file and set it to a different variable so we do not have to write out long code every time we want to read the csv file.

To make thins easier later on, we sorted the dates into acending order to keep the code and the graph neat concise.

We then checked some components of the csv file using .info and .head function calls. .info is used to see the datatypes and basic information of the function while the .head(#) is to show you a preview of the data to whatever # of columns you want.

**Explaining Part 3:**

We set the parameters for the x-axis to be from 2020 to 2021. This is because we do not want irrelevant data. Covid-19 only became prevalent worldwide as a pandemic from 2020 onward.

We also made a list of the countried we want to be in the graph: The U.S., China, and Russia.

We had to make different calls to read specific parts of the code for each country because countries are subsections of the same column.

**Explaining Part 4:**

This part is where we actually graph the information we want. The graph contains the Covid Rates for each country. As you can see, many other countries handled containing the COVID-19 pandemic better than the United States. China was stern on regulations while other countries were not. Also, Russia was effective as well.

In the end, we can only watch our mistakes and choose not to do them in the future.
