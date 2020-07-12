# Communicate-Data-Finding
# Prosper Loan Dataset Exploration
## by Swati Chanchal
Preliminary Wrangling
This is a datset of Proser Loans , Prosper makes personal loans easy. Whether you're consolidating debt or remodeling your home, we have a solution for you. This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. (Last updated 03/11/2014)

## What is the structure of your dataset?
This data set contains 113,937 loans with 81 variables . Rows = 113,937 and Columns = 81

## What is/are the main feature(s) of interest in your dataset?
There are so many variables in this dataset.Trying to figure out what features can be used to predict .

## What features in the dataset do you think will help support your investigation into your feature(s) of interest?
According to me the features which going to help me are Borrower Monthly Payment, Borrower Occupation, Borrower State, Borrower Employment Status , Borrower Rate, Borrower APR, Prosper Score, Loan Amount .

## Discuss the distribution(s) of your variable(s) of interest. Were there any unusual points? Did you need to perform any transformations?
All the graph I plotted , mostly are normally distributed .In the case of Borrower state there is a great difference between the 1st highest state(california ) and 2nd highest state(Texas) .I don't think transformation is needed as I'm just investigating the datset .

## Of the features you investigated, were there any unusual distributions? Did you perform any operations on the data to tidy, adjust, or change the form of the data? If so, why did you do this?
In case of original loan amount (loan original amount) I found that it is Multimodel . A multimodal distribution is a probability distribution with more than one peak, or “mode.”

## Talk about some of the relationships you observed in this part of the investigation. How did the feature(s) of interest vary with other features in the dataset?
Loan Amount : loan amounts keep increasing with the year . Borrower Rate and Borrower APR keep up increasing and decreasing . Borrower rate is highest for 2008 , 2009 , 2010 Employed Browwers have highest Prosper Rting .

## Did you observe any interesting relationships between the other features (not the main feature(s) of interest)?
I found Prosper rating , Is borrower owned home and Ocupation intresting .

## Talk about some of the relationships you observed in this part of the investigation. Were there features that strengthened each other in terms of looking at your feature(s) of interest?
Prosper Rating is very low for Loan Status other than Completed and Current . Not Employed Borrower have Low prosper score . The borrower with high income range have high prosper rating

## Were there any interesting or surprising interactions between features?
Prosper Rating and Employment Status : Non- Employed have the lowest rating , Employed have the highest rating .
