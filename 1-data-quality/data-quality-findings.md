# Data quality findings

My deliverable for the first module was an email to the client that set out the data quality issues I found in the four worksheets (Transactions, NewCustomerList, CustomerDemographic and CustomerAddress). The greeting, the request and the sign-off followed the template email in the brief, so only my own findings are kept here. The checks behind them are in [`exploration.ipynb`](exploration.ipynb).

> I notice some irregular data entries which may affect the future analysis.
>
> Here are the problems I found in each dataset, please take a look to ensure these data points are correct.

| Datasets             | Problems                                                                                                               |
| -------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| Transaction          | found 0 product id                                                                                                     |
| Transaction          | unknown data type of product_first_sold_date                                                                           |
| NewCustomerList      | there are four unknown column names after property_valuation and before Rank                                           |
| NewCustomerList      | missing values exist from in following attributes: last_name, DOB, job_title, job_industry_category                    |
| NewCustomerList      | rank attribute doesn't contain unique values, need be double checked                                                   |
| CustomerDemographics | missing values exist in the following attributes: last_name, DOB, job_title, job_industry_category, default and tenure |
| CustomerDemographics | inconsistent date entry in gender attribute                                                                            |
| CustomerDemographics | row index 33 has a DOB of 1843-12-21 which is impossible                                                               |
| CustomerDemographics | default attribute contains unknown characters                                                                          |
