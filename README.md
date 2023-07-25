# Data Analysis Project -- Indian Start-up Funding Analysis

Ideas, creativity, and execution are essential for a start-up to
flourish. But are they enough? Investors provide start-ups and other
entrepreneurial ventures with the capital---popularly known as
\"funding\"---to think big, grow rich, and leave a lasting impact. In
this project, you are going to analyse funding received by start-ups in
India from 2018 to 2021. You will find the data for each year of funding
in a separate csv file in the dataset provided. In these files you\'ll
find the start-ups' details, the funding amounts received, and the
investors\' information.

**Column names and description:**

-   **Company/Brand**: Name of the company/start-up

-   **Founded**: Year start-up was founded

-   **Sector**: Sector of service

-   **What it does**: Description about Company

-   **Founders**: Founders of the Company

-   **Investor**: Investors

-   **Amount(\$)**: Raised fund

-   **Stage**: Round of funding reached

## Scenario 

Your team is trying to venture into the Indian start-up ecosystem. As the 
data expert of the team you are to investigate the ecosystem and propose 
the best course of action. 

## Instructions

Your task is to develop a unique story from this dataset by stating and
testing a hypothesis, asking questions, perform analysis and share
insights with appropriate visualisations.

So as part of the project you are to:

-   Ask questions

-   Develop hypothesis

-   Process the data

-   Analyse the data

-   Visualise the data

Upon completion compile these processes in a blog post and share your
analysis on Medium, LinkedIn, Dev.to, personal blog or a suitable
blogging website.



## Data Processing: Technics used in Data cleaning

1. Data Inspection

2. Dealing with Missing Data

3. Handling Duplicates

4. Data Transformation

5. Outlier Detection and Treatment

6. Data Integration

7. Feature Engineering


## Hypothesis :

-  1. - Null hypothesis: The stage of a company has no impact on the amount of funding it receives.

      - Alternative hypothesis: The stage of a company has impact on the amount of funding it receives.

-  2. - Null hypothesis: The location of a company has no impact on the amount of funding it receives.

      - Alternative hypothesis: The location of a company has impact on the amount of funding it receives.

-  3. - Null hypothesis: The sector of a company has no impact on the amount of funding it receives.

      - Alternative hypothesis: The sector of a company has impact on the amount of funding it receives.


## Questions:

-   1. Which 5 sectors attracted the largest funding?

-   2. What is the range of funds (max_Amount, min_Amount, mean_Amount, median_Amount, std_Amount of funding)? in the dataset?

-   3. Which are 5 top sectors with most companies?

-   4. Which are the top 5 companies in the funding amounts?

-   5. Are there any outliers in the funding amounts in the datasets?

-   6. Which top 5 locations have the highest number of companies in the datasets?

-   7. What is the range of funds (max_Amount, min_Amount, mean_Amount, median_Amount, std_Amount of funding)? in the location with the highest number of companies.

-   8. What is the trend in startup funding in India over the years (2018-2021) ? 


## Insights and Recommendations

### 1.Trend in Startup Funding

The trend in startup funding in India has shown that there is consistent growth over the years. From 2018 to 2019, there was a decrease, and from 2019 to 2021, there was a remarkable growth in the total funding amount accessed by Indian startups. This indicates a positive transformation and increasing investor interest in the Indian startup ecosystem. Startups should showcase their potential and seeking funding opportunities during this favorable period.

### 2.Relationship between Startup stage and Funding.

The stage of a company has no impact on the amount of funding it receives. This implies that the stage alone may not be a determining factor in securing funding. Startups from various stages have received funding, and therefore, it is important for startups to focus on other factors such as their value proposition, business model, and growth potential when seeking funding.

### 3.Relationship between Startup location and Funding.

The location of a company has no impact on the amount of funding it receives. The analysis did not find a significant relationship between the location of a startup's headquarters and the amount of funding they receive. This suggests that the location alone may not be a decisive factor in funding decisions. Startups should focus on other aspects

### 4.Relationship between Startup sector and Funding.

The sector of a company has no impact on the amount of funding it receives. The analysis did not find a significant relationship between the sector of a startup's headquarters and the amount of funding they receive. This suggests that the location alone may not be a decisive factor in funding decisions. Startups should focus on other aspects

### 5.Startups regional distribution

Bangalore has the highest number of startups in the dataset, followed by Mumbai, Gurugram, and New Delhi. These cities have a thriving startup ecosystem and offer various resources, networking opportunities, and investor presence. Startups should consider these cities as potential locations to establish their operations and leverage the supportive startup ecosystem.

### 6.Funding regional distribution

Mumbai has the highest funding Amount in the dataset, followed by California, and Bangalore. 

### 7.Startups sector distribution

FinTech has the highest number of startups in the dataset, followed by EdTech, Financial and Ecommerce. 

### 8.Funding sector distribution

FinTech has the highest number of startups in the dataset, followed by Retail,EdTech, and TechCompany. 

## Conclusion

In conclusion, while the sector, location and stage of a startup may not have a significant impact on funding outcomes, startups can enhance their chances of securing funding by focusing on factors such as market potential, value proposition, team expertise, and adapting their fundraising strategies based on market trends and investor preferences.

## Workflow

Open this https://github.com/imalexianne/LP1_Data_Analysis/blob/master/Indian-start-up-funding-ecosystem-analysis.ipynb for further exploration.


## Setup
Install the required packages to be able to run the evaluation locally.

You need to have [`Python 3`](https://www.python.org/) on your system (**a Python version lower than 3.10**). Then you can clone this repo and being at the repo's `root :: repository_name> ...`  follow the steps below:


- Windows *(Python should be added to the Path variable of environment)*:
        
        python3 -m venv venv; venv\Scripts\activate; python -m pip install --upgrade pip; python -m pip install -r requirements.txt  

- Linux & MacOs:
        
        python3 -m venv venv; source venv/bin/activate; python -m pip install --upgrade pip; python -m pip install -r requirements.txt

The both long command-lines have a same structure, they pipe multiple commands using the symbol **;** but you may manually execute them one after another.

1. **Create the Python's virtual environment** that isolates the required libraries of the project to avoid conflicts;
2. **Activate the Python's virtual environment** so that the Python kernel & libraries will be those of the isolated environment;
3. **Upgrade Pip, the installed libraries/packages manager** to have the up-to-date version that will work correctly;
4. **Install the required libraries/packages** listed in the `requirements.txt` file so that it will be allow to import them into the python's scripts and notebooks without any issue.

## Recap table

|  Power Bi link            | LinkedIn article link                       | GitHub's Link                                       |
|:------------------------:|:----------------------------------:|:---------------------------------------------------:|
| https://app.powerbi.com/groups/me/reports/d51236d1-072f-403f-acf7-5db0aef624da?pbi_source=desktop       |  https://www.linkedin.com/pulse/in-depth-analysis-indian-start-up-funding-trends-imanirakarama/    |https://github.com/imalexianne/LP1_Data_Analysis/tree/master      |

