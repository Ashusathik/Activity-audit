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

<img width="1919" height="964" alt="Screenshot 2026-09-05 005100" src="https://github.com/user-attachments/assets/cf42affc-7916-4c69-87b5-2f177801ddf3" />


## 2.	CloudTrail Event History 

<img width="1919" height="967" alt="Screenshot 2026-09-05 005126" src="https://github.com/user-attachments/assets/7215e71b-a83c-4730-957c-742119af8aa2" />


## 3.	CreateBucket Event Details 

<img width="1919" height="960" alt="Screenshot 2026-09-05 005218" src="https://github.com/user-attachments/assets/9c1ca331-a46e-4b80-b97c-69c00977ccbf" />


## 4.	Second CloudTrail Event Details 

<img width="1919" height="961" alt="Screenshot 2026-09-05 005339" src="https://github.com/user-attachments/assets/e45890bb-cb0f-43a1-a5ae-4d8a74c11af7" />


## 5.	Final Audit/Observation Table


<img width="1919" height="970" alt="Screenshot 2026-09-05 005513" src="https://github.com/user-attachments/assets/2f6ead5a-85ed-44d0-80e9-76bea3725a7f" />


### Result

The cloud activities in AWS were successfully audited using AWS CloudTrail Event History. The events were analyzed based on user identity, event name, event time, event source, AWS Region, read-only status, and error status, demonstrating CloudTrail's role in monitoring and accountability. 
