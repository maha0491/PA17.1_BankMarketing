# PA17.1_BankMarketing
Practical Application Assignment 17.1: Comparing Classifiers
Link to Notebook: 

To whom it may concern,

I am writing to you in respose to your inquiry with regards to what model increases campaign efficiency by determining which factors help to secure clients who subscribe to term deposits. When I first reviewed your data that you had provided, I noticed that you provided 20 feature variables and 41,188 client records. 
The 20 feature variables that you had provided are the following Age, Job, Marital Status, Education, if they have Credit in Default, if they have Housing Loans, if they have Personal Loan, Contact Communication Type, Last Contact MOnth of Year, Last Contact Day of the Week, Last Contact Duration, Number of Contacts Performed During this Campaign and for this Client, Number of Days that Passed by After the Client was Last Contacted from a Previous Campaign, Number of Contacts Performed before this Campaign and for This Client, Outcome of the Previous Marketing Campaign, Employement Variation Rate, Consumer Price Index, Consumer Confidence Index, Euribor 3 Month Rate, and Number of Employees. 
Upon analyzing the data, I also noticed that your records of clients who had subscribed to term deposits versus those who had not subscribed were vastly unbalanced. ![Target_Proportions](https://github.com/user-attachments/assets/815f21a3-2277-42b5-a2ad-6cb509743964). 
#### Despite this unbalance in the result, I had decided to use a modeling method to determine what are the key 5 factors that help in determining if a client will be subscribing to a term deposit. Using this modeling method, I was able to determing that the 5 key factors that influence the decision are Employment Variation Rate, Call Duration, Consumer Price Index, Euribor 3 Month Rate, and Contact Communication Type. Each of these 5 variable also had unbalanced distributions but combined, made up a strong model. I had determined this result with about a 91% accuracy confidence.
For example, the Call Duration distribution was skewed with significant values that were well above the average range.![Duration_Distribution](https://github.com/user-attachments/assets/b4b07c38-4a76-4d98-82c5-e73439d0d88c)
Additionally, the Contact Communication type displayed a greater proportion using cell phones in comparison to landlines.![Contact_Proportions](https://github.com/user-attachments/assets/1f52acb4-e16e-4104-b9dc-ae086576bd50)

I had decided to compare this result against another 3 other modeling methods and received similar results with equally high confidence results. The 3 other modeling methods similarly had about 90% to 91% Accuracy values as well.
#### I believe that your next steps would be to primarily target your Employement Variation Rate, the Durations of the Contact Calls, your Consumer Price Index, Euribor 3 Month Rate, and the form of communication that your Clients are using.

Sincerely,
Mahalakshmi Ganesan
