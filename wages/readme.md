## Wages Repo
I'm interested in investigating how Obama's [new overtime rules](https://www.dol.gov/whd/overtime/final2016/) change the incentive for employees in salary negotiation. Much like the economics of the earned income tax credit ([graph](http://d2vlcm61l7u1fs.cloudfront.net/media%2F845%2F845d8be7-72e7-41a2-88b9-42f5a9e72576%2FphpJwfZ3l.png)), it changes the utility-maximizing point for employees in the labor market. Unlike the EITC, however, it may encourage employees to request a lower listed salary so that they are still within the guaranteed overtime ceiling.

### Current status

I'm building out the methods necessary to calculate an individual's "actual income" in Python. Given two inputs `salaryOffered` and `estimatedWeeklyHours`, I can calculate the true per hour wage. Using that per hour wage, I can calculate the true compensation, based on if that person is doing overtime or not. 

This is all currently done in the static-graphs.py file