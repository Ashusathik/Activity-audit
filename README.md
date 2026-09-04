# Activity-audit

# AUDITING CLOUD ACTIVITY USING AWS CLOUDTRAIL

### Aim

To audit and monitor cloud activity in AWS using AWS CloudTrail by viewing and analyzing recorded AWS events.

### Requirements

* AWS Account
* Web Browser
* Internet Connection
* Amazon S3 access
* AWS CloudTrail

### Procedure

1. Log in to the AWS Management Console and open **AWS CloudTrail**.
2. Select **Event history** to view recent AWS activity.
3. Select an S3-related `CreateBucket` event and open its details.
4. Record the **Event Time, User Name, Event Name, Event Source, AWS Region, Read-only status, and Error Code**.
5. Return to Event history and select another CloudTrail event.
6. Open the event details and record the important audit information.
7. Compare both events based on their time, user, event name, service, region, read-only status, error status, and activity.
8. Identify **who, what, when, where, and result** for each event.
9. Prepare the final audit/observation table using the recorded information.
10. Capture screenshots of the CloudTrail dashboard, Event History, event details, and final audit table.

The experiment procedure and required observations are based on the uploaded Experiment 5 document.  

### Output:

## 1.	AWS CloudTrail Dashboard 

<img width="1917" height="1047" alt="image" src="https://github.com/user-attachments/assets/60274fa1-5512-49c8-96d5-492eb6fd7503" />


## 2.	CloudTrail Event History 

<img width="1917" height="1042" alt="image" src="https://github.com/user-attachments/assets/b37d6889-919b-47c9-a424-bf7750196050" />


## 3.	CreateBucket Event Details 

<img width="1917" height="1052" alt="image" src="https://github.com/user-attachments/assets/8ba87e32-2717-4289-9932-de243cfcf569" />


## 4.	Second CloudTrail Event Details 

<img width="1917" height="1048" alt="image" src="https://github.com/user-attachments/assets/cd898252-6fba-485c-a5b6-5c493d5aa1b1" />


## 5.	Final Audit/Observation Table

<img width="1917" height="1042" alt="image" src="https://github.com/user-attachments/assets/e122135d-f36f-4794-a3ff-bef64428db47" />



### Result

The cloud activities in AWS were successfully audited using AWS CloudTrail Event History. The events were analyzed based on user identity, event name, event time, event source, AWS Region, read-only status, and error status, demonstrating CloudTrail's role in monitoring and accountability. 
