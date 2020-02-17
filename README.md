# web_scraper
When I first heard about data science, I did not really sure where should I start and what the path is to become a Data Scientist. After countless hours of research my conclusion about what the job consists of was unclear. What I had discovered in my research was how this job title is rapidly growing into a demanding career option. Living in a time of enormous amounts of data, more and more companies are in demand and looking to fill this position. I began to question, how do you become a data scientist, what degree or level of education do you need, what skills are employers looking for? This lead me to explore the job applications, backgrounds, experiences, and skills that the current data scientist possess. So the data analysis begins! first, I scrape LinkedIn job and I supposed with this I would gather job descriptions and key skills demanding. Second I am going to scrape individuals who land the job as a Data Scientist. For the first part I will go with getting insights from job descriptions. Let ‘s start scraping!


### The Web-scrape:
I had to decide on what country and job title to pull job information from. I decided to go with United Kingdom due to the enormous amounts of applications for data scientists and the English language standard libraries for analyzing text data. 

>First, I do not condone scraping LinkedIn data in any way. Anyone who wishes to do so should first read <a href = 'https://www.linkedin.com/help/linkedin/answer/56347/prohibition-of-scraping-software?lang=enprohibition'>  LinkedIn's statement </a> on their of scraping software. 

>Also, note that LinkedIn actively suspends accounts due to <b>excessive activity</b> on a given account.

This code is to be used for learning purposes only and should not be used a tool for any commercial purpose. 

I used selenium and beautiful soup to web-scrape job application in United Kingdom in LinkedIn. 
When searching through the list of job application on LinkedIn, it will show a number of pages with 25 job applications on each page. After your first page, to continue scraping on to the next set of 25 job applications you have to get to the next page. Using selenium helped me maneuver around this issue. Selenium has a restriction on its speed because the scraping with the browser is much slower. Due to the slowness, to not get banned by LinkedIn the use of the "sleep" statements had to be used in my code multiple times to cause further slow-down. I write every job applicant to a csv file.



