# AWS-Experience
Documentation of my experience with AWS Services for Cloud Computing. The purpose of this module was to design and implement a Data Pipeline for Data Analytics.

### Project Info:
Tasks
You are to build a data engineering solution that uses many AWS services that are familiar
to you. You have decided to build the infrastructure in your AWS Academy environment and
test it by using at least four data files for your choice (e.g. 2 countries and 2 species) from
the given data source.

By working with this variety of data files, you will be able to test whether the solution that
you build can support a much larger dataset in actual implementation.
The objective of this project is to achieve a sustainable and seamless data synchronization
and better front-end data service for data consumption. Prior to building a robust and reliable
solution, you shall start with an architecture design proposal (which is considered as a
Project Report) and viable prototype (which is considered as a Project Solution) in this
context. The aim of the prototype is to present the Proof of Concept (POC) to judge the
feasibility for actual implementation.

### This project will challenge you to do the following:
#### Basic Requirements
- Using AWS Cloud9 integrated development environment (IDE) instance.
- Collect and ingest the data from the web source.
- Store the data in Amazon S3 and create a data catalogue.
- Create an AWS Glue crawler to infer the structure of the data, transform the data to be
in human readable format (such as CSV).
- Use Amazon Athena to query the data and create the views for analysis purpose.
- Create an analysis dashboard in Amazon Quick-Sight for the data visualization using
the data outputted from the Athena Query Result.
#### Advanced Requirements
- Data Wrangling (further data processing using boto, AWS Data Wrangler and other
relevant Python libraries)
- Deployment (using API and Step functions)
- Monitoring and Notifications
- Advanced Data Visualization with further insights in (Tableau or Power BI or Jupyter
Notebook)

### Pipeline Design:
![image](https://github.com/Javen05/AWS-Experience/assets/107395637/cb1d7199-dea3-439f-bf8e-d6caeaf8f5ef)
[Link to Diagram](https://app.diagrams.net/#G13J0cF2yyGpaR7hjSbrzBRWiW_HM7i7L0)

### Difference between Version 1 and 2:
Version 2 aimed to fulfil the advanced requirements of the project. Decided to strategically focus on USA fisheries in order to integrate the USA.json and species datasets together. Also created S3 API endpoint in order to connect to Power BI to create visualizations using live data from my created API to achieve 'Advanced Analytics' requirement.

