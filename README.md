# LENDING CLUB CASE STUDY
> Lending club case study for understanding the patterns in loan defaulters via EDA.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
**Objective:** Use EDA to find out key attributes which influence the tendency to default

**Group Members** (Individual)
* Atul Tiwari

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
**Interest Rate**
* Charged off (defaulters) proportion increases with increase in interest rates. Interest rate more than 16% has the highest chance of charged off. 
* Interest rates increases with increase in loan amount. 
* From the above two points it is justified why loan amount of 20000+ has high chances of charged off.

**Pupose of Loan**
* Top 3 defaulters categories with respect to purpose of loan are - 
a. Small Business applicants 
b. Renewable energy applicants
c. Educational applicants

**Annual Income**
* Low annual income range people are more likely to default. Income range (0-20000) has high chances of charged off.

**Grade**
* Proportion of charged off applicants are more with grade moving from "A" towards "F".
* One of the reason for increasing proportion of charged off applicants while moving from grade "A" towards grade "F" can be attributed to increased interest rate as grade moves from A to F.

**Employment Length**
* Employment length of less than one year has highest proportion of charged off loan applicants. 

**Home Ownership**
* With respect to home ownership highest applicant numbers are for those living in rented home. Next highest loan applicants are those who mortgaged their home. But Charge off chances is less in case of mortgaged homes. Charge off chances are more in case of other categories.

**DTI**
* Chances of charged off applicants increased with the increase in DTI.

**Loan Term**
* Charged off applicants numbers are higher in case of 60 months loan term.
* Interest rate is higher in case of 60 months loan term, leading to increased Charged off applicants.

**Public Record Bankruptcies**
* Higher number of Public Record Bankruptcies results in higher rate of Charged off applicants.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- python
- numpy
- pandas
- matplotlib
- seaborn
- dataprep

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Contact
Created by [@atultiwari] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->