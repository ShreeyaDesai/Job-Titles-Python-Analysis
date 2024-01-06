# Mentions-Of-Job-Titles-Python-Analysis

**Purpose:**
This Python script analyzes comments from a Hacker News thread to identify mentions of specific job titles. It then performs basic operations on the keyword counts and generates two types of visualizations: a bar plot and a pie chart.

**Dependencies:**
pandas: Data manipulation library (although not used explicitly in the script)
keyword: Python's built-in module for accessing keywords
requests: HTTP library for making requests
bs4 (Beautiful Soup): HTML parsing library
matplotlib: Plotting library
statistics: Statistical functions library
google.colab: Colab-specific library for file handling

**Steps:
Data Retrieval:**
The script sends an HTTP request to a Hacker News thread and parses the HTML using BeautifulSoup.
It extracts comments and looks for mentions of specific job titles, such as "engineering," "developer," "designers," "devops," and "research."

**Keyword Counting:**
The script counts the occurrences of the specified job titles in the comments.

**Basic Operations:**
Basic statistical operations (sum, min, max, mean, median, mode) are performed on the keyword counts.

**Graph Generation - Bar Plot:**
A bar plot is created to visualize the frequency of job title mentions in the comments.
The graph is saved as 'graph3-1.png' and can be downloaded.

**Graph Generation - Pie Chart:**
A pie chart is generated to illustrate the distribution of job title mentions.
The graph is saved as 'graph3-2.png' and can be downloaded.

**Usage:**
Run the script in a Colab environment.
Examine and download the bar plot ('graph3-1.png') displaying job title mentions.
Examine and download the pie chart ('graph3-2.png') illustrating the distribution of job title mentions.
