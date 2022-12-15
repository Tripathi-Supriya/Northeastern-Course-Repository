# Northeastern-Course-Repository

One stop resource for all course related information at Northeastern University.  

## Team Members: 

- Ishika Misal (email: misal.i@northeastern.edu, NUID: 002787945)
- Utkarsha Shirke (email: shirke.u@northeastern.edu NUID: 002797914 )
- Supriya Tripathi (email: tripathi.su@northeastern.edu NUID: 002770986)

## Project Description: 

This project aims to create a database containing all relevant resources. The resources database will include: 

- Programs offered on the Boston campus of Northeastern University in the College of Engineering, and details about their duration, offerings, and specializations. 
- The relevant study material (paid and free resources) for all courses offered by COE. 
- Tools and software required by the courses.  
- Future career outcomes post-degree completion. 

We aspire to help learners through our initiative by helping them collate the resources they need to navigate their course. 

## Scope: 

We have shortlisted 3 graduate degree programs offered by Northeastern University’s College Of Engineering.  Our database is built around these programs. 
- Masters of Science in Information Systems (MSIS)
- Masters of Science in Data Analytics Engineering (MS DAE)
- Masters of Science Software Engineering Systems (MS CSYE)

## Strategy:



## Implementation

## Phase 1: Twitter 

We started with thorough research and collection of existing data pertaining to this project. We sought various sources of data and verified the existing ones. To begin with, we laid out the use cases which we were seeking answers for. As the next steps, we spoke to a bunch of students at Northeastern University to gather information and factor in their points of view. 

Moving forward, we sought broader sources of information which led us to Twitter. Since Twitter as a platform voices many opinions, we thought it would give us a good sense of our project space. We scraped Twitter API, using tweepy for relevant programs, courses, and resources offered by Northeastern university, tweets, information about users, and their posts related to our database. This was a good starting point for our database and it helped us to move in the right direction. 

The performed the following steps for above analysis: 

- Fetched data from twitter 
- Inserted that data in our database using MYSQL
- Performed Queries to view data related to courses, programs, faculty details, events, and users. 
- Aligned and corraborated our usecases with the data collected using Twitter API 

#### Please visit the following link to get a detailed view of our Twitter data analysis
https://github.com/Tripathi-Supriya/Northeastern-Course-Repository/tree/main/Twitter%20Bot


## Phase 2: Gathering data from multiple resources

After collecting data from twitter, we condenseed our search to three main sources for data collection, described as follows: 

#### Website Scraping: 
As most of the details about the course offerings are available on the Northeastern university’s website, we have scraped multiple pages to gather information in one place. 

#### API Scraping: 
We have scraped LinkedIn API to collect information about the jobs a student can secure after graduating from the courses within our scope. We have used Python and Scrapy to get job-related data. We used the ai-skunks GitHub as a starting point to get jobs-related data. 

#### Google Forms: 
To get more on-ground data, we spoke to a few students and circulated google forms to collect data pertaining to resources that are relevant to the aforementioned programs. 

#### Google form Link to collect data:
https://docs.google.com/forms/d/e/1FAIpQLSfrdYENonfpEiqz62068CAPzFMHxywHvGfN4KWWV_0_zlkFOQ/formResponse
https://docs.google.com/forms/d/e/1FAIpQLSdQA2PA0DnS3jZjijo3N6l_oaYShjSEPOj0YfJWczVFrZ2KjQ/viewform

We have collated all the above data sources to create a database and established connections between program offerings, jobs related to these programs, events conducted to promote jobs and programs, and the resources learners need to excel in their coursework. To fetch the data we ran Python Script for scraping NEU Websites in Jupyter Notebook and Linkedin API Script for Scraping jobs on Linkedin. We also cleaned the data to fit our usecase using Python and MYSQL. 


#### Please visit the following link to get a detailed view of Phase 2
https://github.com/Tripathi-Supriya/Northeastern-Course-Repository/tree/main/Assignment_3_WebScrape

## Phase 3: Normalization

The data collected in Phase 2 was sufficient but it was not in standard format. The final phase of this project involved normalizing this data. We studied all the tables obtained in the second phase extensively and realised that some tables were violating the some normal forms viz. 1NF, 2NF, and 3NF. We have documeneted all these changes in a separate detailed folder. 

#### Please visit the following link to get a detailed view Normalization conducted in Phase 3
https://github.com/Tripathi-Supriya/Northeastern-Course-Repository/tree/main/Assignment_4

Here's a brief overview of the dataset obtained after the final phase

### Newly Created Table for Normalization:


## UseCases 

## Conclusion

Our database now contains, easy to use tables, which have details relevnat to MSIS, SES, and CSYE programs offered at Northeasetrn University. Students can use this database to make informed decisions about their coursework, facult, events, and career related outcomes. 


