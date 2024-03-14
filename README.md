The particular requirement given here was to create a new related record which could be achieved with the help of a record triggered flow.
I have preferred flow here instead of going for a coding approach as per the best practice suggested by Salesforce. 
The flow is triggered whenever a case record is edited to have type as 'Problem' and does not have a related record already present. 
To check for the permissions to do so, I have referenced Permission Set assignment record to check if the Current user has the Case Admin Permission Set assigned or not.
