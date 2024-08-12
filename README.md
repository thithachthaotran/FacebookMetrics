# FacebookMetrics
Reading and writing a CSV File: Process a UCI Dataset
Goal
UCI datasets are often stored in csv format.  In this exercise, you will download a dataset and do some processing on it.

Python Notebook
Use a new Python Notebook to do the following.

First, download the Facebook Metrics dataset at the UCI repository.  (Hint: Use wget, as in previous week Activities.)

The dataset is in csv format, with the delimiter ';'.  You'll be focussing on columns 1 ("Type") and 7 ("Lifetime Post Total Reach").  The types are Photo, Status, Link, Video.  For each of these types, calculate the average lifetime post total reach. Write the result in a suitable CSV file.

Python Script
Repeat the above, but as a Python script in your VM.  It should expect one argument, the name of the csv file.  (Hint: Use argparse, as in last week's Activity's koppel11.py code.)
