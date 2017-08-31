Data Team Project
================================

This is a project that we use for testing potential team members of the Data Team and their technical skills.

## Assignment

Build a simple analytics platform for a Fake Insurance company using the Kaggle dataset **[Agency Performance Model](https://www.kaggle.com/moneystore/agencyperformance)**. This platform has two components: API and key user web app.

## Minimum Requirements

- Build an Data Pipeline/ETL process that takes the CSVs as input and saves into a database at a detailed level and also calculates summary views. These summary view could follow star schema or any other that you think will allow for querying using different views/dimensions. The Data Pipeline can be manually triggered by running a script (include instructions of how to do it!) or automated somehow.
- Build an API (REST, Graph or other design pattern) that provides:
  - Detailed information using a different parameters (like agency, month, year, state, etc)
  - Summarized information using different parameters (like agency, month, year, state, etc)
  - An XLS, XLSX or CSV report with Premium info by Agency and Product Line using a date range as parameters
- Build a web app that includes at least one chart and tables with the detailed and summarized data
- The web app should also be able to build/run the report by specifying the start and end date to use
- The Data Pipeline/ETL process and also the logic for generating the report must be done using Pandas
- Deployment to any PaaS vendor/host (AWS, Heroku, Digital Ocean, etc.)

### ETL/Data Pipeline Flow

![](https://raw.githubusercontent.com/IntuitiveWebSolutions/DataTeamProject/master/data_pipeline.png)

### Use Cases

![](https://raw.githubusercontent.com/IntuitiveWebSolutions/DataTeamProject/master/use_cases.png)

## Tech Stack Requirements

The following are requirements on the tech stack. This stack demonstrates mastery of tools our team favors:

- OS: Ubuntu
- Server Side Scripting: Python 2.7+ or 3.5+ and Pandas for the API and report
- Server Framework: Flask or SimpleHTTPServer
- JavaScript: We use KnockoutJS and Vue JS for newer modules and apps

Make sure that your instructions for accessing or otherwise running your code are extremely clear.

### Bonus points

- Integration or Unit tests (at least one of those). You can use `pytest` or `unittest`
- Authentication so that only authorized users can query the API
- Deployment in AWS ECS for the web server/API
- Deployment in AWS RDS for the database/backend
- Good test coverage
- Documented code and that follows pep8 and The Zen of Python
- API documentation
- Using docker for deployment
- Using other AWS stack components relevant for Data Engineering (Lambdas, S3, DynamoDb, Cognito, etc.)
- Using any CI service like Travis, Shippable, Circle CI, etc. for running the tests
- Including other reports, tables, dashboards, KPIs or useful analytics
- Incremental ETL that only processes and loads new records

## Guidelines

Build your own public repo on GitHub, and call it whatever you like. Build your solution in your repo, and include a `README.md` file that contains the detailed instructions for running your platform. Prior to submission, please bring up a live hosted example. AWS has a free tier if you aren't certain where to host. Once your project is completed, please email ivan@britecore.com.

We're looking for someone who can work independently and self curious, this is why one of the major goals in this project is to see how you fill in ambiguities in your own creative way. There is no such thing as a perfect project here, just interpretations of the instructions above, so be creative in your approach but feel free to email ivan@britecore.com for any questions you may have.

Thank you for your time. We are excited to review your project!
