# ByteWizards Data Analytics Project 2020
#### Semester-5 project for Data Analytics(UE18CS312)

## Introduction
One of the most important things in a job search is
knowing where you stand in your career and where do you
want to go next. The mindset of a job seeker is very much like
a product manager, trying to find the best product and a
market fit. Smart product managers know what their
customers want. So, they carefully find out customers’ needs
which are expressed through “top qualifications”, “what you
must have”, in the job descriptions. After identifying what is
commonly needed in the market, smart product managers will
customize their products aka resumes, cover letters, online
profiles, portfolios to demonstrate these characteristics and
traits as much as possible.

Accurate recruitment of employees is a key element
in the business strategy of every company due to its impact
on companies’ productivity and competitiveness. At present
recruitment processes have evolved into tedious tasks
involving rigorous evaluations and interviews of candidates,
intending to hire the best-suited professionals for each
company’s needs. With the advent of the Internet and the
web, e-Recruitment has become an essential element of all
hiring strategies. Many websites, such as CareerBuilder,
Monster or even Social Networks, like LinkedIn, help
companies and job seekers to find the best possible matches.

The dataset chosen for this project is “Data Analyst Jobs” from
Kaggle which has job listings from companies scraped from
the Glassdoor website. We first go about a survey of various
papers in the domain to get some knowledge on the various
techniques and models used for the same. We then perform
an extensive data wrangling and exploratory data analysis.
We find relation between different aspects of this dataset and
add extract details from the dataset to be used for
recommendation and any further analysis. Job
recommendation is a very extensive task in today’s world, so
we try to bring forth a simpler approach based on skills of
each candidate in this pandemic situation

## Jaccard Coefficient
A Jaccard Coefficient function was created to
calculate the similarity, and based on the user input skills on
what job will be the best for the particular user. 

Jaccard Coefficient was used as the requirement of the company was
based on the provided skills, and not on all possible skills.
Thereby the Jaccard Coefficient was taken, rather than
Cosine Similarity for our dataset.

<img src="https://render.githubusercontent.com/render/math?math=J = {|A \cup B|/|A \cap B| }">

## How to read the pickled data
```
import pickle
pickle_in = open("CleanedDataAnalyst.pickle", "rb")
df = pickle.load(pickle_in)
pickle.close()

df.head()
```

## Team Members:
- <b>Name:</b> Afzal Mukhtar<br><b>SRN:</b> PES2201800675 
- <b>Name:</b> Aswin A Nair<br><b>SRN:</b> PES2201800504 
- <b>Name:</b> Hritika Rahul Mehta<br><b>SRN:</b> PES201800024
