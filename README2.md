# Quickly Detecting Anomalies in Web site traffic

---

***Final Project, FAES BIOF 309 Introduction to Python, Fall 2018***

**Marie Gallagher, mgallagher@mail.nih.gov**

## Background

Part of my job is to provide statistics about Web site use.
Various Web analytics software have been mandated over time by my institute,
including: awstats, WebTrends and Google Analytics.

Each piece of software analyzes and reports differently,
usually creating the appearance of a massive increase or decrease
in traffic when we start using different Web analytics software.

I need some consistent indicator so I can tell if there is a legitimate,
unexpected change in the Web site traffic.

Unique IP addresses per day turns out to be a reasonably reliable indicator.

My data contains the number of unique IP addresses 
accessing a Web site each day.

A quick visualization of this data would help me quickly spot anomalies.

## Demo

- Development environment: Anaconda Distribution and JetBrains PyCharm on Windows 10.

- A few lines of my data:

```
06/01/2018|5565|515120|515120|515120
06/02/2018|4801|518657|518657|518657
06/03/2018|4069|451881|451881|451881
06/04/2018|4859|493762|493762|493762
06/05/2018|4816|514587|514587|514587
```

- There are no column headers in this data.

- The columns are separated by the pipe character rather than commas, spaces or tabs.

- We are interested in the first two columns, and we want to ignore the rest of the columns.

- The first column contains date information, but it is in the form MM/DD/YYYY rather than YYYY-MM-DD.

- Code is in [./code/plot_unique_ips.py](./code/plot_unique_ips.py)


## Future

1. I will incorporate this project into my work immediately.    (Until now, I imported the data into Excel and made a graph.)

2. Break my program into functions and restructure my project files

3. Scrub IP addresses from raw log files and extract data from them

4. List the most accessed URLs on days with high IP address counts

5. List the top referrers on days with high IP address counts

## Acknowledgments and Thanks!

BIOF 309 Instructors
* Martin Skarzynski
* Jinping Liu
* Michael Chambers

BIOF 309 Class
* Helpful questions

NIAID Scientific Programming Seminars through CIT
* Burke Squires

## See this final project template

[https://github.com/marskar/final-project-template](https://github.com/marskar/final-project-template)
