# AWS infrastructure task
version 1

## Requirements
- use AWS free tier accounts for your team deployment
- use OS images of debian-11 
- populate the README.md documentation file on how the virtual infrastructure was created

# Infrastructure environment for data collection
In Amazon Web services, create the necessary resources, which will host the crawling application and data from the Data collection task.


## Requirements
- Create an AWS free-tier account for your team
- Create virtual machine of the appropriate type 
- Configure SSH access for all team members
- Configure git access from the GitHub private repo
- Install and configure all the necessary packages - Python, sqLite3, prometheus, graphana, etc.
- Deploy the crawling application on the prepared VM
- Configure local monitoring with Prometheus and Graphana of
  - basic monitoring of system resources
  - the crawler and database processes
  - create and configure mail alerting for failed runs

Task Bonus Points - Docker:
- Install a docker image which will host the crawler and crawled data 
- Deploy and start the crawling process in the installed docker image
- Reuild the crawling docker image to save the changes and create a crawler docker image
- Create/clone a testing instance from the rebuilt crawling docker image
- Define git hooks for deployment to the test environemnt on commit
- Implement a deployment process between the two docker images
- Install and configure 
- Configure system and application monitoring for the crawling docker
