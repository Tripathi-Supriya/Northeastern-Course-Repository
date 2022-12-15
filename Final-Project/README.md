# Northeastern-Course-Repository
NEU resource for courses offered. 

# Team Members: 

Ishika Misal (email: misal.i@northeastern.edu)
Utkarsha Shirke (email: shirke.u@northeastern.edu )
Supriya Tripathi (email: tripathi.su@northeastern.edu)

# Project Description: 

This project aims to create a database containing all relevant resources. The resources database will include: 

- Programs offered on the Boston campus of Northeastern University in the College of Engineering, and details about their duration, offerings, and specializations. 
- The relevant study material (paid and free resources) for all courses offered by COE. 
- Tools and software required by the courses.  
- Future career outcomes post-degree completion. 

We aspire to help learners through our initiative by helping them collate the resources they need to navigate their course. 

## Scope: 
We have shortlisted 3 graduate degree programs offered by Northeastern University’s College Of Engineering.  Our database is built around these programs. 
Masters of Science in Information Systems
Masters of Science in Data Analytics Engineering
Masters of Science Software Engineering Systems

## Plan of Action:
We have used 3 sources to collect the data: 

### Website Scraping: 
As most of the details about the course offerings are available on the Northeastern university’s website, we have scraped multiple pages to gather information in one place. 

### API Scraping: 
We have scraped LinkedIn API to collect information about the jobs a student can secure after graduating from the courses within our scope. We have used Python and Scrapy to get job-related data. We used the ai-skunks GitHub as a starting point to get jobs-related data. 

### Google Forms: 
To get more on-ground data, we spoke to a few students and circulated google forms to collect data pertaining to resources that are relevant to the aforementioned programs. 

#### Google form Link to collect data:
https://docs.google.com/forms/d/e/1FAIpQLSfrdYENonfpEiqz62068CAPzFMHxywHvGfN4KWWV_0_zlkFOQ/formResponse
https://docs.google.com/forms/d/e/1FAIpQLSdQA2PA0DnS3jZjijo3N6l_oaYShjSEPOj0YfJWczVFrZ2KjQ/viewform

We have collated all the above data sources to create a database and established connections between program offerings, jobs related to these programs, events conducted to promote jobs and programs, and the resources learners need to excel in their coursework. 

## Part 1 of the project (Twitter Bot)
The first step towards this is by using data extracted via Twitter pertinent to programs, courses, and resources offered by Northeastern university. We have written a twitter bot that gets tweets, user details, tweet tags, and tweet mentions relevant to our project- Northeastern-Course-Repository.

# Assignment Execution Steps:
- Fetched data from twitter 
- Inserted that data in MYSQL tables
- Performed Queries to view data related to courses, programs, faculty details and events
- UseCases and relational algebra

# Conclusion
Twitter is one of the most widely used social platforms. It contains large pool of data(Information) which we used to collect meaningful data for our database Course repository. With this application students will be able to easily access the data that they need such as courses available this team, professor details, free study resourses and events happening around campus. 

# To view the execution steps in details click on the link
https://github.com/Tripathi-Supriya/Northeastern-Course-Repository/tree/main/Twitter%20Bot
    
    
### Part 2 of the project (Gathering, Scraping, Munging and Cleaning Data)
For this assignment we collected data from 3 sources mentioned above and executed and perfomed data cleaning in tables.
To fetch the data we ran Python Script for scraping NEU Websites in Jupyter Notebook and Linkedin API Script for Scraping jobs on Linkedin.
To check the Accuracy, Completeness and Uniformity of the data we implemented the steps shown below to ensuring data is correct.

NEU_Programs Table:
- Removed all programs name which were not in Boston in the dataframe using drop duplicates command in python

Neu_Course_Catalog Table:
- Unwanted text removed in python after scraping data and then inserted into table.

NEU_Course_Faculty Table:
- Data inserted from csv file by collecting responses from Students

Resource_Material1 Table:
- Data inserted from csv file as per responses given by students

NEU_Event Table:
- This data is manually inserted in SQL by using insert query. Hence, the data is validated and then inserted into table

NEU_Specialization Table:
- Data is validated beffore inserting into table.

Course_Core_Requirement Table:
- Accurate data scraped from Northeastern University website. No cleaning required

Jobs_Info Table:
- Duplicate jobs are removed from the scraped data in jupyter notebook


### Part 3 of the project (Normalization)



## Newly Created Table for Normalization:




## UseCases 


## Conclusion 
Normalization is the process to eliminate data redundancy and enhance data integrity in the table. 



